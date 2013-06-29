## Code style

1.use double quotation marks, example:

    style=""

2.has a blank before and after the operator, example: 

    1 + 1 = 2

3.something about bracket and brace will like this : 

    function(arg) {
        do sth;
    }
    
    if (true) {
        do sth;
    } else {
        do sth;
    }
    
    for (var i; i < 5; i++) {
        do sth;
    }

4.have a blank after colon, semicolen and comma, example:

    margin: 5px;
    for (var i; i < 5; i++)
    test(arg1, arg2, arg3)

5.if the arg has [], means mot must value, example:

    join(${1:[separator]});

## Format of this doc

### shotcut name
the content will display if you use this shotcut

> the ${num} means when you press "tab" key, the the cursor moving order.

- - - 

## HTML snippet

### css1
    <link rel="stylesheet" type="text/css" href="${1}" />

### css2
    <style type="text/css">
        ${1}
    </style>

### icon
    <link rel="shortcut icon" href="favicon.ico">

### js1
    <script type="text/javascript" src="${1}"></script>

### js2
    <script type="text/javascript">
        ${1}
    </script>

### st
    style="$1"

### ula
    <ul class="$1">
        <li><a href="$1"></a></li>
    	<li><a href="$2"></a></li>
    	<li><a href="$3"></a></li>
    </ul>

### ulai
    <ul class="$1">
        <li><a href=""><img src="" alt=""></a></li>
    	<li><a href=""><img src="" alt=""></a></li>
    	<li><a href=""><img src="" alt=""></a></li>
    </ul>

- - - 

## CSS snippet

### bgc
    background: #${1};

### bgi
    background: url(../img/${1}) no-repeat;

### brr
    border-radius: ${1}px ${2}px ${3}px ${4}px;

### brrsame
    border-radius: ${1}px;

### colorc
    color: #${1};

### fll
    float: left;

### flr
    float: right;

### fzp
    font-size: ${1}px;

### hightp
    height: ${1}px;

### mtp
    margin-top: ${1}px;

### mar0
    margin: 0 auto;

### marginp
    margin: ${1}px ${2}px ${3}px ${4}px;

### marsame
    margin: ${1}px;

### mbp
    margin-bottom: ${1}px;

### mlp
    margin-left: ${1}px;

### mrp
    margin-right: ${1}px;

### mtp
    margin-top: ${1}px;

### paddingp
    padding: ${1}px ${2}px ${3}px ${4}px;

### pasame
    padding: ${1}px;

### pbp
    padding-bottom: ${1}px;

### plp
    padding-left: ${1}px;

### prp
    padding-right: ${1}px;

### ptp
    padding-top: ${1}px;

### tac
    text-align: center;

### testbr
    border: 3px solid #${1};

### widthfull
    width: 100%;

### widthp
    width: ${1}px;

- - - 

## JavaScript snippet

### alert
    alert("${1:message}");

### clearTimeout
    clearTimeout(setTimeout_variable);

### clearInterval
    clearInterval(setTimeout_variable);

### concat
    concat(${1:arrayX,arrayX,......,arrayX});

### Date
    Date();

### for
    for(${1:1}; ${2:2}; ${3:3}) {
        ${4:4}
    }

### funlk
    function ${1:name}(${2:arg}) { 
       ${3}
    }

### getFullYear
    getFullYear();

### getHours
    getHours();

### getid
    document.getElementById("${1:id_name}");

### getMinutes
    getMinutes();

### getMonth
    getMonth();

### getSeconds
    getSeconds();

### gettag
    document.getElementsByTagName("${1:tag_name}");

### if
    if(${1:1condition}) {
        ${2:2func}
    }

### ifelse
    if(${1:1condition}) {
        ${2:2func}
    }
    else {
    	${3:3func}
    }

### indexOf
    indexOf(${1:1searchvalue}${2:[,2fromindex]});

### isNaN
    isNaN();

### join
    join(${1:[separator]});

### log
    console.log(${1:"message"});

### max
    max({$1:x}, {$2:y});

### min
    min({$1:x}, {$2:y});

### Object
    Object();

### parseFloat
    parseFloat($1);

### parseInt
    parseInt($1);

### pop
    pop();

### pow
    pow({$1:x}, {$2:y});

### push
    push(${1:newelement1,newelement2,....});

### random
    random();

### replace
    replace();

### round
    round($1);

### setInterval
    ${1:arg} = setInterval(
       function() {
           ${2:content}  
        }, ${3:time}
    );

### setTimeout
    ${1:arg} = setTimeout(
       function() {
           ${2:content}  
        }, ${3:time}
    );
    
### switch
    switch(${1:1}) {
       case "${2:2}": ${3:3}; break;
       case "${4:4}": ${5:5}; break;
    }

### shift
    shift();

### slice
    slice(${1:1start(include)}, ${2:2end(not_include)});

### sort
    sort(${1:[sortby]});

### splice
    splice(${1:1index}, ${2:2howmany}, ${3:3element1,.....,elementX});

### sqrt
    sqrt($1);

### substr
    substr(${1:1start(include)}, ${2:2length});

### switch
    switch(${1:1}) {
        case "${2:2}": ${3:3}; break;
        case "${4:4}": ${5:5}; break;
    }

### toLowerCase
    toLowerCase();

### toString
    toString();

### toUpperCase
    toUpperCase();

### while
    while(${1:1condition}) {
        ${2:2func}
    }

- - - 

## jQuery snippet

### ajax
    $.ajax({
       type: "${1:1POST/GET}",
       url: "${2:2root_path}",
       data: {
           ${3:data_name}: ${4:5data_val}
       }
    }).done(function(msg) {
        ${5:5content}
    }).fail(function() {
        ${6:6content}
    };

### animate
    animate({"${1:property}": "${2:val}"}, ${3:time})

### append
    append("${1:content}")

### attr
    attr("${1:attributeName}", "${2:[value]}")

### before
    before("${1:insert_content}")

### bind
    bind(${1:1event}, function(){
        ${2:2func}
    });

### blur
    blur()

### change
    change(function(){
        ${1:func}
    });

### docready
    $(document).ready(function() {  
       aaa
    });

### get
    $.get("${1:1root_path}", { 
        ${2:2data_name}: ${3:3data_val}
    },
    function(msg){
        ${4:4content}
    });
    

### hover
    hover(function(){
       ${1:mouseenter}
    },function(){
       ${2:mouseleave}
    });

### mouseenter
    mouseenter(function(){
       ${1:content}
    });

### mouseleave
    mouseleave(function(){
       ${1:content}
    });

### post
    $.post("${1:1root_path}", { 
        ${2:2data_name}: ${3:3data_val}
    },
    function(msg){
        ${4:4content}
    });    

### selector
    $("${1:name}").${2:fun}

