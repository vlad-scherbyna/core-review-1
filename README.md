Implement the functionality with which it will be possible to receive user data in the desired format.

The userId will be passed to the input as a string.
Depending on the user's role, different data should be returned.
There are currently 2 such formats:

If the role is ```admin``` then the ```name```, ```role```, ```password``` and ```permissions``` fields are returned.
If the role is ```regular``` then ```name``` and ```role```.

Formats may change in the future.

The ```permissions``` field must be in pascal-case and parsed only from valid values: ```reportStats```, ```validate```.

These fields are also may change in the future.
