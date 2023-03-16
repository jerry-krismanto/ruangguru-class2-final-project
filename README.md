PSEUDOCODE CASHIER

START

DECLARE total_price = x = 0
DECLARE confirm = false

WHILE confirm = false
	INPUT item
	READ item
	PRINT item_price
	x += item_price
	INPUT user done OR user not done
	if user done
		confirm = true
	else
		confirm = false

PRINT x

END

