---
published: true
title: Search problem
layout: post
---
```javascript
var state, goalState;
function isAchievedGoal() {
  return initialState === goalState;
}

function action(initialState){
  // blah.....blah
  return nextState;
}

(function(){
  while(!isAchievedGoal()){
    state = action(state)
  }
}())
```
