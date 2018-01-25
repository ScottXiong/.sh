# .sh
```

#!/bin/bash
a=1
while [ $a -lt 1000 ]
do
	mkdir -p test$a;
	echo " I love you for almost $a years";
	a=$[$a+1]
	if[ $a=19 ]
		rm -rf test*
done
```
