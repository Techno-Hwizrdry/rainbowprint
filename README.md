# rainbowprint
A Python 3 module that allows you to print your command line output in pretty colors.  Print the rainbow!

## Prerequisites
This module requires python3 (version 3.6 or later) and python3-pip.

These prerequisites can be installed on a Debian based linux machine, like so:

`sudo apt-get install python3 python3-pip`

## Installing

Via Python pip:

`pip install rainbowprint-TechnoHwizrdry`

## Usage
Import the rprint function, like so:

`from rainbowprint import rprint`

Use the rprint() function to print any object you want (string, boolean, integer, etc.):

```python
from rainbowprint import rprint

rainbow_chicken = '''
B5YG&@@@@@@@@@BY&@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@&BJ!Y#@@@@@@@@57&@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@B~:J&@@@@@@&:7@@@@@@@J#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@&~.~B@@@@@@~.5@@@@@@~?@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@G:.^B@@@@&^.!@@@@@P:~@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@7::~&@@@?::^&@@@5:.7@@@@@@@&@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@P::.P@@?.:.7@#Y~:.^B@@@@@&?Y@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@5.:.?@Y.:.~BJ:...~B@@@&G?:^B@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@7.:.?&^:.!G!.:.^Y@@B57^.:?&@##@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@7.:.55.:!G^.:~YGP7^..:~Y#@G7~#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@?...5!.^G^.~Y57:..^75B#G?^.!#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@G...::.^~.:J!::~?PBB57^.:7G@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@B............:!JY7^...~J5PG@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@5 .............. .....::^P@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@G......~?~............. .:?#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@P~...:JJ7...............  :Y@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@#J7~:....................  ~B@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@P555Y?^.................... .5@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@&55555PP!....................  J@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@B5PGPPGY...................... ~?5B&@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@&#@&&&&5^ ....................   .:!YG&@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@&J.........................  .^7P&@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@G:.........:::::::::::::.....  :?G@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@P.....:::::::::::::::::::::.... .~Y#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@~...::::::::::::::::::::::::::..  .~YB&@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@G..::::::::::::::::::::::::::::::..  .^75#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@Y.::::::::::::::::::::::::::::::::::..  .^?P#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@J..:::::::::::::::::::::::::::::::::::...  .~?P#@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@Y..::::::::::::::::::::::::::::::::::::::...  .^?5B@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@G^..:::::::::::::::::::::::::::::::::::::::....  .^75B&@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@&?...:::::::::::::::::::::::::::::::::::::::::....  .:!YG&@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@B!....:::::::::::::::::::::::::::::::::::::::::.....  .:~JP#@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@P!. ...:::::::::::::::::::::::::::::::::::::::::......   .^?5B&@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@BY!:......:::::::::::::::::::::::::::::::.:::::::........  .^!YB@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@B!.:............................       ...................  .!G@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@&7::::::..~YJ??777!!!!!!!!!777??JJY5Y7~:.   ............. .   !
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@&!::::::.P@@@@@@@@@@@@@@@@@@@@@@@@@@@@#B5J!^:..  ..... !J7!!7Y
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@P::::::.G@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#BPY?!~^:^?&@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@#P55555PPP5Y?!~~^^:::7Y5GB&@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@&&&@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@##GJ5J!!!!!!!7?????JJJJJJYGB&@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
'''

rprint(rainbow_chicken.replace('@', ' '))
```

The resulting output will look like this:

![Rainbow Chicken](https://siasky.net/RAA5FuYo-Wbj8Zb-wnynTteP5cyzgNVDxEGui5H-Muuo5Q)

You can select a color sequence by passing the 'seq' argument, like so:

`rprint('Some example text', seq=1)`

There are currently only two gradients to choose from [0 or 1].  More will be added in future releases.  If no seq argument is passed, then rprint will default to sequence 0.

If seq=1, you can also pass a start and end color as well:

`rprint('Some example text', seq=1, start='blue', end='white')`

'start' and 'end' are optional, and their defaults are 'red' and 'blue' respectively.

The optional arguments for python's print() can also be passed to rprint():

`rprint('Some example text', seq=1, sep=None, end='', file=None, flush=True)`

## Functions

#### rprint(text: object, seq: int = 0, **kwargs) -> None
Prints text in color pattern, based on the selected sequence (seq).
This function can also take the same arguments as Python's print()
via **kwargs.

#### magenta_gradient() -> Generator[int, None, None]
Generates an integer that corresponds to a color in this gradient.

#### basic_gradient(start: str='', end: str='') -> Generator[int, None, None]
Generates an integer that corresponds to a color in this gradient.
A start color and an end color can be specified via the start and
end parameters.  The default start and end are 'red'
and 'blue' respectively.
