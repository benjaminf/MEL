bf :: MELUtils Prototypes
---------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------
MELUtils is a set of proc made to help MELScripters.

---------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------
		int bf_parseBoolFlagsFromString (string $FLAGS, int $PARSED_BOOL_FLAGS[]);			
			
			/-/	Arguments:
				//	string $FLAGS[] : a string of boolean flags. AKA : string $flags="1|0|1|0|...".
				//  int $PARSED_BOOL_FLAGS[] : an array which will hold the boolean flags.
			
			/-/	Return:
				//	1 : Success + $PARSED_BOOL_FLAGS[] filed with the flags in order.
				//	0 : Error + 'emptied'($PARSED_BOOL_FLAGS[]).
			
			/-/	Usage:		
				//	int $FLAGS[];
				//	string $strFlAGS="1|0|1";
				
				//	if (bf_parseBoolFlagsFromString($strFlAGS,$FLAGS))
				//	{	
				//		yourProc($FLAGS);
				//	}
---------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------