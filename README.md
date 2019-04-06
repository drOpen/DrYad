# DrYad
yet alternative human-readable data serialization language


**- Types:**
	**- null**
		null value= *null*
	**- bool** - *holds value that can be only *true* or *false*. The keywords *true* and *false* correspond to the two states.*
		bool value= *false*
		bool array= *true, false*
		bool array= *false, false, true,*
		bool array with single element= *true,*
		bool array without any element= null bool
	**- int** - *holds signed 32 bit integers that range in value from -2,147,483,648 through 2,147,483,647.*
		int value= *0*
		int minimum value= *-2147483648*
		int maximum value= *2147483647*
		int array= *0, -1, 1*
		int array with single lement= *777,*
		int array without any element= null int

