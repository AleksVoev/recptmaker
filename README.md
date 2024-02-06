# recptmaker
Receipt generator for Capriotti's.

NOTES:

Receipt survey codes for Capriottis are generated in the following manner:

1. The first three digits are the order numbers rearranged to place the last digit in the first slot and move the other numbers down. Ex: 154 - 415, 102 - 210.

2. The next three digits are the day and date in the following format (d-mm) for example the first of January would be 101. However, if a date is double-digit, the only number being used will be the second number. Ex: September 22nd is 209

3. The following 3 digits are separators, which are 000 and remain static.

4. Lastly, the rest of the 6 digits seem to be static, and could possibly pertain to some store metric such as the store's number. Unsure as of the moment, however, the digits are "053-023"

5.  Putting all those digits together will create the 15-digit code such as "015502000053023"
