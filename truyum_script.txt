function add(){
    alert("item added successfully");
}
function deleted(){
    alert("item deleted");
}
function valid(){
    var name=document.getElementById("name").value;
    var price=document.getElementById("prc").value;
    var dl=document.getElementById("dol")
    if(name=="")
    alert("Please enter name");
    if(price=="")
    alert("Please enter name");
    if(dl=="")
    alert("please enter date of launch");
}