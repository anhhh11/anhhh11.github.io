---
published: false
title: Admissible heuristic - static
layout: post
---
```
You again control a single insect, but there are B birds flying along known paths. Specifically, at time t each bird b will be at position (xb(t),yb(t)). The tuple of bird positions repeats with period T. Birds might move up to 3 squares per time step. An example is shown below, but keep in mind that you should answer for a general instance of the problem, not simply the map and path shown below.
```
<img src="https://d37djvu3ytnwxt.cloudfront.net/assets/courseware/v1/a0815d5bf52b86fa1193b9cc2f2c6183/c4x/BerkeleyX/CS188x_1/asset/hw1_maze_birds.png" />
```
Which of the following is a minimal state representation?
1. A tuple (x,y) giving the position of the insect, plus an integer r=t mod T where t is the time step.

Which of the following heuristics are admissible (if any)?
2. Manhattan distance from the insect's current position to the nearest bird. -> No
3. Manhattan distance from the insect's current position to the target divided by three. -> Yes
```
> Thông số nào có thể cố định thì hãy cố định và sử dụng biến số một các hàm súc(consise) nhất, ý (1)
>
> Việc làm lỏng vấn đề(relax) có thể ảnh hướng đến giả thiết căn bản của vấn đề, cần chú ý, ý (2), (3).
