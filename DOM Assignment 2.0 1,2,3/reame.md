# *DOM Asignment*
*DOM Asignment 1*
___
## Task 1

The user has to append a new element in the navigation menue named **"Hire Me"** after **Projects**.

### **After Updates**
![Output Image](./firstAssignmentImage/task1Output.png)

### **Project Solution**
```js
let a=document.querySelector("ul");
let b=document.createElement("li");
b.innerHTML="<a>Hire Me</a>";
a.appendChild(b);
```
## Task 2

The user needs to change placeholder to "Search My Project" from "Search" 

### **After Updates**
![Output Image](./firstAssignmentImage/task2Output.png)

### **Project Solution**
```js
let element = document.querySelector("input");
element.placeholder="Search My Project";
``` 
## Task 3

The user has to change the "a frelancer" to " an Employee" and "National and International client" to "iNeuron Intelligence Pvt Ltd"

### **After Updates**
![Output Image](./firstAssignmentImage/task3Output.png)

### **Project Solution**
```js
let a = document.querySelector("p").children;
a.item(2).innerText="an employee";
a.item(4).innerText="I Neuron Inteligence Pvt Ltd";
``` 
## Task 4

The user needs to change "avtar" image to image of "hitesh sir"

### **After Updates**
![Output Image](./firstAssignmentImage/task4Output.png)

### **Project Solution**
```js
let img=document.querySelector(".hero-right-section");
img.querySelector("img").src="https://tse4.mm.bing.net/th?id=OIP.rKAdI6dNQGgJOcrbGbIq5QHaHa&pid=Api&P=0";
``` 

## Task 5

The user has to create one more button having name "Support Me"

### **After Updates**
![Output Image](./firstAssignmentImage/task5Output.png)

### **Project Solution**
```js
let newbtn=document.createElement("button");
let parrent=document.querySelector(".hero-right-section-btns");
parrent.appendChild(newbtn);

``` 
___
*DOM Asignment 2*
___
## Task 1

The user has to append a new element in the navigation menue named **"Hire Me"** after **Projects**.

### **After Updates**
![Output Image](./secondAssignmentImage/task1Output.png)

### **Project Solution**
```js
let head= document.querySelectorAll(".accordian h3");
let para= document.querySelectorAll(".accordian p");
head.forEach((element)=>{element.style.backgroundColor="#dadaf8"});
para.forEach((element)=>{element.style.backgroundColor="#eeeeff"});
```


## Task 2

The user has to append a new element in the navigation menue named **"Hire Me"** after **Projects**.

### **After Updates**
![Output Image](./secondAssignmentImage/task2Output.png)

### **Project Solution**
```js
let parent=document.querySelector(".accordian-wrapper");
let newelement=document.createElement("div");
newelement.className="accordian";
let head=document.createElement("h3");
let para=document.createElement("p");
head.innerText="Skills"
para.innerText="I posses a very good command over the Full Stack Development technologies like MERN which can be seen in my work over the Github."
newelement.appendChild(head);
newelement.appendChild(para);
parent.appendChild(newelement);


```

___
*DOM Asignment 3*
___
## Task 1

The user has to append a new element in the navigation menue named **"Hire Me"** after **Projects**.

### **After Updates**
![Output Image](./thirdAssignmentImage/task1Output.png)

### **Project Solution**
```js
document.querySelector(".enterName").placeholder="FSJS 2.0";
document.querySelector(".enterMail").placeholder="fsjs@ineuron.ai"
document.querySelector(".enterMessage").placeholder="Hello world";
document.querySelector(".userName").placeholder="FSJS 2.0";
document.querySelector(".userEmail").placeholder="fsjs@ineuron.ai"
document.querySelector(".userMessage").placeholder="Hello world";

```

___
*DOM Asignment 4*
___
## Task 1

The user has to append a new element in the navigation menue named **"Hire Me"** after **Projects**.

### **After Updates**
![Output Image](../04_DOM%20Project/04_DOM%20Project/Output/DOM%20P1%20SS.png)

### **Project Solution**
```js
document.querySelector(".clearfix").style.backgroundColor="#EC9B3B";
document.querySelector(".clearfix").style.color="#FFFFFF";
document.querySelector(".clash-card__unit-stats--archer").style.backgroundColor="#EE5487";
document.querySelector(".clash-card__unit-stats--archer").style.color="#FFFFFF";
document.querySelector(".clash-card__unit-stats--giant").style.backgroundColor="#F6901A";
document.querySelector(".clash-card__unit-stats--giant").style.color="#FFFFFF";
document.querySelector(".clash-card__unit-stats--goblin").style.backgroundColor="#82BB30";
document.querySelector(".clash-card__unit-stats--goblin").style.color="#fff";
document.querySelector(".clash-card__unit-stats--wizard").style.backgroundColor="#4FACFF";
document.querySelector(".clash-card__unit-stats--wizard").style.color="#fff";
document.querySelector(".clash-card__unit-stats--archer").children.item(2).style.color="#FFF";
document.querySelector(".clash-card__unit-stats--giant").children.item(2).style.color="#FFF";
document.querySelector(".clash-card__unit-stats--goblin").children.item(2).style.color="#FFF";
document.querySelector(".clash-card__unit-stats--wizard").children.item(2).style.color="#FFF";
document.querySelector(".clearfix").children.item(2).style.color="#FFF";
```

___
*DOM Asignment 5*
___
## Task 1
**Projects**.

### **After Updates**
![Output Image](../05_DOM%20Project/05_DOM%20Project/Output/DOM%20P2%20SS.png)

### **Project Solution**
```js
let newbtn=document.createElement("a");
newbtn.className="btn";
newbtn.innerText="Pro Subscriptiion";
let parent=document.querySelector(".nav-center").children.item(2);
parent.appendChild(newbtn);

```

___
*DOM Asignment 6*
___
## Task 1
**Projects**.

### **After Updates**
![Output Image](../06_DOM%20Project/06_DOM%20Project/Output/DOM%20P3%20SS-1.png)



### **Project Solution**
```js
document.querySelector("header img").src="https://jobs.ineuron.ai/images/ineuron-logo.png"
```
## Task 2
![Output Image](../06_DOM%20Project/06_DOM%20Project/Output/DOM%20P3%20SS-2.png)

### **Project Solution**
```js
document.querySelector(".app_price span").innerText="$10";
let parent=document.querySelector(".footer_social");
let child=document.createElement("div");
child.className="footer_social_ico";
child.innerHTML="<i></i>"
child.querySelector("i").className="fa-brands fa-linkedin"
parent.appendChild(child);
```

DOM Asignment 7*
___
## Task 1
**Projects**.
### **Before Updates**
![Output Image](../DOM%20P7/DOM%20P7/ass7.1-before.png)

### **After Updates**
![Output Image](../DOM%20P7/DOM%20P7/ass7.1-after.png)

### **Project Solution**
```js
let j2 = document.querySelector(".main__languages");
for (let n=3; n<8; n++){
j2.removeChild(j2.children.item(n));
}
```

## Task 2
**Projects**.
### **Before Updates**
![Output Image](../DOM%20P7/DOM%20P7/ass7.2-before.png)

### **After Updates**
![Output Image](../DOM%20P7/DOM%20P7/ass7.2-after.png)


### **Project Solution**
```js
let btn =document.querySelector(".main__form-btn");
btn.addEventListener("click", function reload(){document.location.reload()});
```

DOM Asignment 8*
___
## Task 1
**Projects**.
### **Before Updates**
![Output Image](../DOM%20P8/DOM%20P8/ass8.1-before.png)
### **After Updates**
![Output Image](../DOM%20P8/DOM%20P8/ass8.1-after.png)
### **Project Solution**
```js
// remove navbar

document.querySelector(".navbar-brand").innerHTML = ""; document.querySelector(".navbar-nav").innerHTML = "";

// add red color border to the div

document.querySelector(".col-lg-4").style.border = "3px solid red";

// add vertical scrollbar

let list = document.querySelector("aside"); let newscrollbar = document.querySelector(".new"); newscrollbar.style.overflowY = "scroll";

// add horizontal line

let aside = document.querySelector(".hr-line"); aside.overflow = "auto"; list.appendChild(aside);

// add h3

let heading = document.querySelector(".new-head"); heading.innerHTML = "This is my custom heading"; list.appendChild(heading);
```

## Task 2
**Projects**.
### **Before Updates**
![Output Image](../DOM%20P8/DOM%20P8/ass8.2-before.png)
### **After Updates**
![Output Image](../DOM%20P8/DOM%20P8/ass8.2-after.png)
### **Project Solution**
```js
let bgc = document.querySelector("body"); bgc.style.background = "#fff";
```

## Task 3
**Projects**.
### **Before Updates**
![Output Image](../DOM%20P8/DOM%20P8/ass8.3-before.png)
### **After Updates**
![Output Image](../DOM%20P8/DOM%20P8/ass8.3-after.png)
### **Project Solution**
```js
let navbartogglebutton = document.querySelector(".navbar-toggler"); navbartogglebutton.addEventListener("click", function(){ document.querySelector("#navbarTogglerDemo01").classList.toggle("collapse"); })
```

DOM Asignment 9*
___
## Task 1
**Projects**.
### **Before Updates**
![Output Image](../DOM%20P9/DOM%20P9/ass9.1-before.png)
### **After Updates**
![Output Image](../DOM%20P9/DOM%20P9/ass9.1-after.png)
### **Project Solution**
```js
let heading=document.querySelector("h1");
heading.style.color="red"

```
## Task 2
**Projects**.
### **Before Updates**
![Output Image](../DOM%20P9/DOM%20P9/ass9.2-before.png)
### **After Updates**
![Output Image](../DOM%20P9/DOM%20P9/ass9.2-after.png)
### **Project Solution**
```js
let btn=document.querySelector(".add-to-cart");
btn.style.backgroundColor="red";
```

