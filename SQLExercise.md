
###*Questions/Queries - Exercise 1*

**How many tweets?**

use bts_s3_vine;
SELECT COUNT(*) FROM vineitems;

Result:
	COUNT(*)
	11826

**Unique vines?**

SELECT COUNT(distinct vine) FROM vineitems;

Result:
	COUNT(distinct vine)
	8955

**Retweets?**

SELECT COUNT(*) FROM vineitems WHERE mex LIKE 'RT%';

Result:
	count(*)
	2837

**Tweets per day?**




> Written with [StackEdit](https://stackedit.io/).
