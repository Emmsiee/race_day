let raceNumber = Math.floor(Math.random() * 1000);

const registeredEarly = true;
const runnerAge = 19;

//runnerAge > 18 ? console.log("You are an adult") : console.log("Not an adult");

if(registeredEarly && runnerAge >= 18) {
  raceNumber += 1000;
}

if(registeredEarly && runnerAge > 18) {
  console.log("You will race at 9:30 am " + raceNumber);
} else if (!registeredEarly && runnerAge > 18 ){
  console.log("Late adults run at 11:00 am " + raceNumber);
} else if (runnerAge < 18 ) {
  console.log("Youth registrants run at 12:30 pm (regardless of registration) " + raceNumber);
} else {
  console.log("Please see the registration desk.");
}
