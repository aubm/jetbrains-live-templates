Usage
=====

## Custom PHP ##

**Alternative if/else syntax**

`aelse`

	<?php if ($COND$): ?>
	    $END$
	<?php else: ?>
	    
	<?php endif; ?>

**Alternative if/elseif/else syntax**

`aelseif`

	<?php if ($COND$): ?>
	    
	<?php elseif ($ELSEIFCOND$): ?>
	    
	<?php else: ?>
	    
	<?php endif; ?>

**Alternative foreach syntax**

`afore`

	<?php foreach ($ARRAY$ as $VAL$): ?>
	    $END$
	<?php endforeach; ?>

**Alternative foreach syntax (with key)**

`aforek`

	<?php foreach ($ARRAY$ as $KEY$ => $VAL$): ?>
	    $END$
	<?php endforeach; ?>

**Alternative if syntax**

`aif`

	<?php if ($COND$): ?>
	    $END$
	<?php endif; ?>

**Class**

`cls`

	class $NAME$
	{
	    $END$
	}

**Class constructor**

`construct`

	public function __construct($ARGS$)
	{
	    $END$
	}

**Dump**

`d`

	var_dump($VAR$);

**Dump & Die**

`dd`

	var_dump($VAR$);
	die();$END$

**If/else**

`else`

	if ($COND$) {
	    $INSTRS$
	} else {
	    $END$
	}

**If/elseif/else**

`elseif`

	if ($COND$) {
	    $INST$
	} elseif ($ELSECOND$) {
	    $INSTELSEIF$
	} else {
	    $END$
	}

**For loop**

`for`

	for ($ITERATOR$; $COND$; $INCR$) {
	    $END$
	}

**For loop with predefined $_i iterator**

`fori`

	for ($_i = 0; $_i < $LIMIT$; $_i++) {
	    $END$
	}

**If**

`if`

	if ($COND$) {
	    $END$
	}

**Swith**

`switch`

	switch ($VAR$) {
	    case $VAL$:
	        $INST$
	        break;
	    default:
	        $DEFAUILT$
	        break;
	}
	$END$