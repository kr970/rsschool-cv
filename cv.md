## Karyna Adamova
-----------------
### Contact information
__Phone:__ +48502299128
__Email:__ kr.adm2318@gmail.com
__GitHub:__ kr970
----------------
### About me
I am a motivated and enthusiastic learner with good problem-solving skills.
I enjoy working in a team and can communicate well with others. 
I always ready to learn new things and improve my skills.
----------------
### Skills
* HTML5, CSS3
* Tailwind
* JavaScript (ES6+)
* TypeScript
* React
* Redux
* GIT
* Figma
---------------
# Code example
__Two Sum: from Leetcode:__ Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.
You may assume that each input would have exactly one solution, and you may not use the same element twice.
```
let twoSum = function (nums, target) {
    let expected = { [target - nums[0]]: 0 };
    for (let i = 1; i < nums.length; i++) {
        if (expected[nums[i]] !== undefined) {
            return [i, expected[nums[i]]]
        } else {
            expected[target - nums[i]] = i;
        }
    }
};
```
----------------
### Education 
__University:__ Master’s Degree in Food Technology and Engineering
__Courses:__ Udemy 
----------------
### Language
__Russian:__ native
__Ukrainian:__ native
__English:__ B1
__Polish:__ A2

