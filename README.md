# goit-js-hw-04

task-1.js: console.log(isEnoughCapacity({ apples: 2, grapes: 3, carrots: 1 },
8));

console.log(isEnoughCapacity({ apples: 4, grapes: 6, lime: 16 }, 12));

console.log(isEnoughCapacity({ apples: 1, lime: 5, tomatoes: 3 }, 14));

task-2.js: console.log( calcAverageCalories([ { day: "monday", calories: 3010 },
{ day: "tuesday", calories: 3200 }, { day: "wednesday", calories: 3120 }, { day:
"thursday", calories: 2900 }, { day: "friday", calories: 3450 }, { day:
"saturday", calories: 3280 }, { day: "sunday", calories: 3300 } ]) ); // 3180

console.log( calcAverageCalories([ { day: "monday", calories: 2040 }, { day:
"tuesday", calories: 2270 }, { day: "wednesday", calories: 2420 }, { day:
"thursday", calories: 1900 }, { day: "friday", calories: 2370 }, { day:
"saturday", calories: 2280 }, { day: "sunday", calories: 2610 } ]) ); // 2270

console.log( calcAverageCalories([]) ); // 0

task-3.js:

console.log(profile.getInfo()); // "Jacob has 300 active hours!"

profile.changeUsername("Marco"); console.log(profile.getInfo()); // "Marco has
300 active hours!"

profile.updatePlayTime(20); console.log(profile.getInfo()); // "Marco has 320
active hours!"
