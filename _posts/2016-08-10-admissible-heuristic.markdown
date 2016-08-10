---
published: true
title: Admissible heuristic
layout: post
---
Question 6: Hive Minds: Swarm Movement

<img src="https://d37djvu3ytnwxt.cloudfront.net/assets/courseware/v1/137f2d4c71360b5c3d153666fdbe2574/c4x/BerkeleyX/CS188x_1/asset/hw1_maze_multi.png" />

```
Which of the following heuristics are admissible (if any)?

(1) Sum of Manhattan distances from each insect's location to its target location.  -> No

(2) Sum of costs of optimal paths for each insect to its goal if it were acting alone in the environment, unobstructed by the other insects.  -> No

(3) Max of Manhattan distances from each insect's location to its target location.  -> Yes

(4) Max of costs of optimal paths for each insect to its goal if it were acting alone in the environment, unobstructed by the other insects. -> Yes

(5) Number of insects that have not yet reached their target location. -> No
```


> Sự điều chỉnh theo kinh nghiệm không nên chỉ dựa theo tổng thể tốt hơn; ý (1),(2)

> Mà sự điều chỉnh này đảm bảo các phần cụ thể trong tổng thể này đều tốt hơn (trong trường hợp từng phần này là liên hệ với nhau); ý (3), (4)

> Không nên chỉ dựa theo sự chưa đạt được về mặt kết quả để đánh giá; ý (5) 