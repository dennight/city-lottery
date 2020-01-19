"use strict";
function randomTwoDigitNumber() {
  let maxNumber = 100;
  let decimalNumber = Math.random() * maxNumber;
  let roundToWhole = Math.floor(decimalNumber);
  return roundToWhole;
}

function lotteryNumbers() {
  let partOne = randomTwoDigitNumber();
  let partTwo = randomTwoDigitNumber();
  let partThree = randomTwoDigitNumber();
  let winningNumbers = partOne + '-' + partTwo + '-' + partThree;
  console.log('Вот номера, принёсшие вам выигрыщ: ' + winningNumbers + '!');
} 

lotteryNumbers();
