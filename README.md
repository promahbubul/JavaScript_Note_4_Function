# JavaScript Function

<details>
<summary>Function</summary>

`function() {}`

```javascript
function greatWorls() {
  console.log("Hello world");
}
greatWorls();
```

### Exercise

```javascript
function getReminder() {
  console.log("Water the palnet");
}
getReminder();
```

```javascript
function getInSpanish() {
  console.log("Buenas Tardes");
}
getInSpanish();
```

</details>
<!-- End fo Functiton -->
<!-- Parameters and Arguments -->
<details> 
  <!-- title -->
<summary> Parameters and Arguments </summary>

  <!-- content -->
```javascript
calculateArea(20, 10);

function calculateArea(width, height) {
  console.log(width * height);
}
    
```
### Exrecise
  <!-- content -->
```javascript
sayThanks("Ashraf");
sayThanks("Siddik");
sayThanks("Jahangir");
sayThanks("Alam");

function sayThanks(name) {
  console.log("Thank you for your parchase " + name + "! We appreciate your business." );
}
```

 </details>
 <!-- End of Parameters and Agruments -->
 <!-- Default Parameters -->
<details> 
<summary> Default Parameters </summary>

```javascript
function animal(name = "Tiger") {
  console.log(`Animal is ${name}`);
  }

  animal("Cow"); // Outpur: Animal  is Tiger
  animal();  // Output: Animal is Tiger

```
### Exercise

<!-- Content -->
```javascript

makeShoppingList();
function makeShoppingList(item1="Milk", item2="Bread", item3="Eggs") {
  console.log(`List: ${item1}, ${item2}, ${item3}`) 
}
```
```javascript

makeShoppingList("Rice", "Alo", "Potato");
function makeShoppingList(item1="Milk", item2="Bread", item3="Eggs") {
  console.log(`List: ${item1}, ${item2}, ${item3}`) 
}
```
 </details>
 <!-- End of Default Parameters -->
 <!--  -->
<details> 
<summary> Return </summary>

without `return`
<!-- Content -->
```javascript
function rectangleArea(width, hight) {
      let area = width * hight
    }
    console.log(rectangleArea(5, 7)) // Prints: Undefined
```
with `return`
<!-- Content -->
```javascript
 function rectangleArea(width, hight) {
      let area = width * hight;
      return area;
      console.log("hello");
    }
    console.log(rectangleArea(5, 7));
```
### Exercise
<!-- Content -->
```javascript
 const numOfMonitors = monitorCount(5, 4);
    console.log(numOfMonitors);

    function monitorCount(rows, columns) {
      return rows * columns;
    }
```
 </details>
 <!-- End of Return -->
 <!-- Helper Function -->
<details> 
<summary> Helper Function </summary>

```javascript

```
 </details>
 <!-- End of Helper Function -->
 <!-- Function Expressions -->
<details> 
<summary> Function Expressions </summary>

```javascript
const plantNeedsWater = function(day) {
        if(day === 'wednesday') {
          return true;
        } else {
          return false
        }
      }
      
      console.log(plantNeedsWater("Thuesday"));
      console.log(plantNeedsWater("wednesday"));
```
 </details>
 <!-- End of Function Expressions -->
 <!-- Arrow Expressions -->
<details> 
<summary> Arrow Expressions </summary>

```javascript
const plantNeedsWater = (day) => {
  if(day === 'wednesday') {
    return true;
  } else {
    return false
  }
}

console.log(plantNeedsWater("Thuesday"));
console.log(plantNeedsWater("wednesday"));
```
 </details>
 <!-- End of Arrow Expressions -->
 <!-- Concise Body Arrow Funciton -->
<details> 
<summary> Concise Body Arrow Funciton </summary>

```javascript
const plantNeedsWater = (day) => day === 'wednesday'
      console.log(plantNeedsWater("Thuesday"));
      console.log(plantNeedsWater("wednesday"));
```
 </details>
 <!-- End of Concise Body Arrow Funciton -->



    