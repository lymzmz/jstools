1.根据id名称取元素  $id(idName) 

2.根据class定义取元素  $class(className)返回所有class被定义成className的元素数组，或者$Eclass(className)返回第一个元素 

3.根据tag名称取元素  $tag(tagName)返回所有标签名称为tagName的元素数组，或者$Etag(tagName)返回第一个元素 

4.父子关系下取元素  $dom(id#idName class#className tag#tagName)返回idName元素下的所有class为className的所有元素的标签名称为tagName的元素数组，或者$Edom(id#idName class#className tag#tagName)返回第一个元素，每个关系之间以空格分隔，对应关系以井号分隔，关系之间可任意顺序 

5.取出来的元素会附带有扩展方法 
    a.getAttr(attrName) 取属性 
    b.setAttr(attrName, attrValue) 设置属性 
    c.getStyle(styleName) 取样式 
    d.setStyle(styleName,styleValue) 设置样式 
    e.getVal() 取值，如果是input,select,textarea取出来的是value的值，其它标签的话取出来的是内嵌html 
    f.setVal(value) 设置值， 如果是input,select,textarea设置的是value的值，其它标签的话设置的是内嵌html  
   g.show() 显示元素 
   h.hide() 隐藏元素 
   
6.AJAX操作使用函数，ajax(type,url,callback,data);  
    a.type  提交类型 
    b.url  提交地址 
    c.callback  回调函数 
    d.data  待提交数据(a=1&b=2) 
    
7.Cookie操作使用函数，cookie.set(k,v,e) k名称  v值  e有效期（秒）   cookie.get(k) 
