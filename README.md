```js
(()=>{const charMap={"S":0,"t":1,"o":2,"p":3," ":4,"f":5,"r":6,"a":7,"s":8,"k":9,"i":10,"n":11,"g":12,"3":13,"y":14,"e":15,"x":16,"c":17,"l":18,"v":19,".":20},indexArray=[0,1,2,3,4,5,2,6,4,7,8,9,10,11,12,4,5,2,6,4,13,4,14,15,7,6,8,4,15,16,3,15,6,10,15,11,17,15,4,5,2,6,4,7,11,4,15,11,1,6,14,4,18,15,19,15,18,4,3,2,8,10,1,10,2,11,20],charArray=Object.keys(charMap).sort((a,b)=>charMap[a]-charMap[b]),rebuildString=indexArray.map(index=>charArray[index]).join('');for(let i=0;i<42;i++)console.log(rebuildString);})();
```
