---
published: true
title: Search problem
layout: post
---
var state, goalState;
function isAchievedGoal() {
  return initialState === goalState;
}

function action(initialState){
  // blah.....blah
  return nextState;
}

go fn(!isAchievedGoal()){
  state = action(state)
}()