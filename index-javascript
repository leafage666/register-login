var usernameValue;

function getCookie(cookieName) {
	var cookie = unescape(document.cookie); //得到解码后的cookie
	var cookieArray = cookie.split(";"); //第一次分组
	for(var i = 0; i < cookieArray.length; i++) { //循环分组里面的内容
		var value = cookieArray[i].split("="); //第二次分组
		if(value[0] == cookieName) { //如果匹配到所要求而的内容
			return value[1]; //返回值
		}
	}
}

function visitor() {
	var div3 = document.createElement("div"); //新建一个div元素节点
	div3.setAttribute("id", "myDiv3"); //设置该div节点id属性为myDiv2
	document.body.appendChild(div3); //将该div插入到body里面
	
	var title = document.createElement("h1"); //新建标题的h1元素节点
	title.setAttribute("id", "title"); //设置id
	var title_text = document.createTextNode("《鹊踏枝》"); //新建一个文本节点
	title.appendChild(title_text); //将该文本节点插入到h1元素节点中
	div3.appendChild(title); //将该元素节点插入到div里面
	
	var content = document.createElement("h1"); //创建内容标点
	content.setAttribute("id", "content"); //设置id属性
	var content_text1 = document.createTextNode("六曲阑干偎碧树，杨柳风轻，展尽黄金缕。");
	var content_text2 = document.createTextNode("谁把钿筝移玉柱？穿帘海燕惊飞去。");
	var content_text3 = document.createTextNode("满眼游丝兼落絮，红杏开时，一霎清明雨。");
	var content_text4 = document.createTextNode("浓睡觉来慵不语，惊残好梦无寻处？"); //添加内容
	content.appendChild(content_text1);
	var br1 = document.createElement("br"); //新建两个换行符
	var br2 = document.createElement("br");
	content.appendChild(br1);
	content.appendChild(br2);
	content.appendChild(content_text2);
	var br3 = document.createElement("br");
	var br4 = document.createElement("br");
	content.appendChild(br3);
	content.appendChild(br4);
	content.appendChild(content_text3);
	var br5 = document.createElement("br");
	var br6 = document.createElement("br");
	content.appendChild(br5);
	content.appendChild(br6);
	content.appendChild(content_text4);
	div3.appendChild(content); //加入到div元素中		
}


function user() {
	visitor();
	var div1 = document.createElement("div");//新建一个div1
	div1.setAttribute("id","myDiv1");//设置id
	var img = document.createElement("img");//新建图片节点
	img.setAttribute("src","run.jpg");
	div1.appendChild(img);//插入到div中
	document.body.appendChild(div1);//插入到body中
	
	var div2 = document.createElement("div");//新建div
	div2.setAttribute("id","myDiv2");
	document.body.appendChild(div2);//添加到body里面
	
	var table = document.createElement("table");//新建table
	div2.appendChild(table);//table插入到div中
	
	var caption = document.createElement("caption");//新建caption标签
	var caption_text = document.createTextNode("Welcome!");//设置文本
	caption.appendChild(caption_text);
	table.appendChild(caption);//插入到表格中
	
	var usernameTr = document.createElement("tr");//新建一行表格
	var usernameTd1 = document.createElement("td");//新建一列表格 存放属性
	var username_text = document.createTextNode("用户：");//设置表格文本
	usernameTd1.appendChild(username_text);//将文本插入到表格中
	var usernameTd2 = document.createElement("td");//再创建一列表格 用来存放值
	var username_value = document.createTextNode(getCookie(usernameValue + "username"));//从cookie中得到想要的值
	usernameTd2.appendChild(username_value);//将值插入到表格中
	usernameTr.appendChild(usernameTd1);
	usernameTr.appendChild(usernameTd2);//依次插入到表格tr中
	table.appendChild(usernameTr);//插入到表格中
	
	var passwordTr = document.createElement("tr");//新建一行表格
	var passwordTd1 = document.createElement("td");//新建一列表格 存放属性
	var password_text = document.createTextNode("用户：");//设置表格文本
	passwordTd1.appendChild(password_text);//将文本插入到表格中
	var passwordTd2 = document.createElement("td");//再创建一列表格 用来存放值
	var password_value = document.createTextNode(getCookie(usernameValue + "password"));//从cookie中得到想要的值
	passwordTd2.appendChild(password_value);//将值插入到表格中
	passwordTr.appendChild(passwordTd1);
	passwordTr.appendChild(passwordTd2);//依次插入到表格tr中
	table.appendChild(passwordTr);//插入到表格中
	
	var mailboxTr = document.createElement("tr");//新建一行表格
	var mailboxTd1 = document.createElement("td");//新建一列表格 存放属性
	var mailbox_text = document.createTextNode("用户：");//设置表格文本
	mailboxTd1.appendChild(mailbox_text);//将文本插入到表格中
	var mailboxTd2 = document.createElement("td");//再创建一列表格 用来存放值
	var mailbox_value = document.createTextNode(getCookie(usernameValue + "mailbox"));//从cookie中得到想要的值
	mailboxTd2.appendChild(mailbox_value);//将值插入到表格中
	mailboxTr.appendChild(mailboxTd1);
	mailboxTr.appendChild(mailboxTd2);//依次插入到表格tr中
	table.appendChild(mailboxTr);//插入到表格中
	
	var phoneTr = document.createElement("tr");//新建一行表格
	var phoneTd1 = document.createElement("td");//新建一列表格 存放属性
	var phone_text = document.createTextNode("用户：");//设置表格文本
	phoneTd1.appendChild(phone_text);//将文本插入到表格中
	var phoneTd2 = document.createElement("td");//再创建一列表格 用来存放值
	var phone_value = document.createTextNode(getCookie(usernameValue + "phone"));//从cookie中得到想要的值
	phoneTd2.appendChild(phone_value);//将值插入到表格中
	phoneTr.appendChild(phoneTd1);
	phoneTr.appendChild(phoneTd2);//依次插入到表格tr中
	table.appendChild(phoneTr);//插入到表格中
}

window.onload = function() {
	var ID = getCookie(" ID"); //得到ID的身份
	if(ID == undefined) {//IE浏览器前面没有空格
		var ID = getCookie("ID");
	}
	var login = getCookie(" login");//得到此时是哪个用户登录的
	if(login == undefined) {
		var login = getCookie("login");
	}
	if(ID == 1) { //如果是用户，加载用户界面
		usernameValue = getCookie(login + "username");
		//alert(usernameValue);
		user();
	}
	if(ID == 0) {
		visitor()//如果是游客，加载游客界面
	}
	if(document.cookie == "") {//如果第一次直接点击游客登录的话，不写入内容
		visitor();
	}
	
}
