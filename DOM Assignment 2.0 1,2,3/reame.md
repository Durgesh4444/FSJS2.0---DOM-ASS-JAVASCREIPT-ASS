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

The user has to append a new element in the navigation menue named **"Hire Me"** after **Projects**.

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

The user has to append a new element in the navigation menue named **"Hire Me"** after **Projects**.

### **After Updates**
![Output Image](../06_DOM%20Project/06_DOM%20Project/Output/DOM%20P3%20SS-1.png)

### **Project Solution**
```js


```