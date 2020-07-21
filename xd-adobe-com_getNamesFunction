
var className = document.getElementsByClassName('singleGridTile-3sBLh');

var nameList = [];

for ( var i = 0; i < className.length; i++) {
	var child = className[i].children[0].getElementsByClassName('artboardTitle-3qs0w')[0].children[0].innerHTML;
	nameList[i] = child;
}

var nameText = nameList.join(',');

var names = nameText.replace(/,/g, '\n');
console.log(names);
