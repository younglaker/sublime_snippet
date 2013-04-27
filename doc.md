## Here is the format of this doc

### shotcut name
the content will display if you use this shotcut

> the ${num} means when you press "tab" key, the the cursor moving order.

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

### getid
    document.getElementById("${1:id_name}");

### gettag
    document.getElementsByTagName("${1:tag_name}");

### funlk
    function ${1:name}(${2:arg}) { 
       ${3}
    }

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

