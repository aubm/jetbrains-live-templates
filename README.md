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

**If set**

`ifset`

	if (isset($VAR$)) {
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

**$this->**

`t`

	$this->$END$

**try / catch**

`try`

	try {
	    $END$
	} catch (\Exception $e) {
	    
	}

## Twig ##

**Block**

`block`

	{% block $NAME$ %}
	    $END$
	{% endblock %}

**Extends**

`extends`

	{% extends '$PARENT$' %}
	$END$

**Filter**

`filter`

	{% filter $NAME$ %}
	    $END$
	{% endfilter %}

**For**

`for`

	{% for $ELEMENT$ in $ARRAY$ %}
	    $END$
	{% endfor %}

**From**

`from`

	{% from '$FILE$' import $ELEMENT$ as $ALIAS$ %}
	$END$

**If**

`if`

	{% if $COND$ %}
	    $END$
	{% endif %}

**Import**

`import`

	{% import '$FILE$' as $ALIAS$ %}
	$END$

**Include**

`include`

	{% include '$FILE$' %}$END$

**Macro**

`macro`

	{% macro $NAME$($ARGS$) %}
	    $END$
	{% endmacro %}

**Set**

`set`

	{% set $NAME$ = $VALUE$ %}$END$

**Spaceless**

`spaceless`

	{% spaceless %}
	    $END$
	{% endspaceless %}