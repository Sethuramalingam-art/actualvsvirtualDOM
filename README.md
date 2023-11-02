# actualvsvirtualDOM

Actual Dom vs Virtual Dom

Actual DOM: DOM stand for Document Object Mode which is tree like representation of html code and describe the structure of the webpage. Manipulating the DOM reduce the performance of the webpage as it re-renders the whole DOM at once.

Virtual DOM: Virtual DOM is an Object representation of the actual DOM which is created when you create react element. React uses React Fiber algorithm.
React Fiber: React fiber is the React core algorithm it includes ability to pause, abort and reuse work as new updates come. React Fiber uses reconciliation process to update the Dom

Reconciliation: Whenever any changes occurs in react component or state variable changes a new Virtual DOM object is created and React triggered the reconciliation process. Now React use diff algorithm to find the difference between the previous virtual DOM and the updated virtual DOM and update the actual dom. 
Note: React update DOM in batches that's why React has faster DOM manipulation ability.
