// JavaScript Document
// List of all players on 40-man Giants roster
const giants40ManRoster = [
  "José Álvarez", "Matthew Boyd", "John Brebbia", "Kervin Castro", "Alex Cobb", "Sam Delaplane",
  "Anthony DeSclafani", "Camilo Doval", "Jarlín García", "Sean Hjelle", "Jakob Junis",
  "Dominic Leone", "Zack Littell", "Mauricio Llovera", "Sam Long", "Yunior Marte",
  "Tobias Myers", "Carlos Rodón", "Randy Rodriguez", "Tyler Rogers", "Angel Rondón",
  "Gregory Santos", "Logan Webb", "Alex Wood", "Alex Young", "Joey Bart", "Curt Casali",
  "Austin Wynns", "Brandon Belt", "Brandon Crawford", "Thairo Estrada", "Wilmer Flores",
  "Tommy La Stella", "Evan Longoria", "Yermín Mercedes", "Darin Ruf", "David Villar",
  "Jason Vosler", "Donovan Walton", "Colton Welker", "Luis González", "Joc Pederson",
  "Heliot Ramos", "Austin Slater", "LaMonte Wade Jr.", "Mike Yastrzemski" ];

// List of active players on Giants roster
const giantsActiveRoster = [
  "John Brebbia", "Alex Cobb", "Camilo Doval", "Jarlín García", "Jakob Junis",
  "Dominic Leone", "Sam Long", "Yunior Marte", "Carlos Rodón", "Tyler Rogers",
  "Logan Webb", "Alex Wood", "Joey Bart", "Austin Wynns", "Brandon Belt",
  "Thairo Estrada", "Wilmer Flores", "Evan Longoria", "Yermín Mercedes", "Darin Ruf",
  "David Villar", "Luis González", "Joc Pederson", "Austin Slater", "LaMonte Wade Jr.",
  "Mike Yastrzemski" ];

// Function that finds players that are in both rosters
function findPlayersOnBothRosters(roster1, roster2) {
  // Only keep players in roster1 who are also in roster2
  return roster1.filter(function(player) {
    return roster2.includes(player);
  });
}

// Function that finds players only in the 40-man roster
function findPlayersOnlyIn40ManRoster(roster40Man, activeRoster) {
  // Keep players in 40-man roster who aren't in active roster
  return roster40Man.filter(function(player) {
    return !activeRoster.includes(player);});
}

// Function counts total unique players across both rosters
function countTotalUniquePlayers(roster1, roster2) {
  // Combine both rosters into one array
  let combinedRoster = roster1.concat(roster2);

  // New array with unique players
  let uniquePlayers = [];

  // Loop through combinedRoster and add new players to uniquePlayers 
  for (let i = 0; i < combinedRoster.length; i++) {
    if (uniquePlayers.indexOf(combinedRoster[i]) === -1) {
      uniquePlayers.push(combinedRoster[i]);
    }
  }

  // Return number of unique players
  return uniquePlayers.length;
}

// Function sorts players by last name in descending order
function sortPlayersByLastNameDescending(playerList) {
  // Copy of the player list
  let playersCopy = playerList.slice();

  // Sort based on their last names
  playersCopy.sort(function(playerA, playerB) {
    // Get last name of each player (last word in the name string)
    let lastNameA = playerA.split(" ").slice(-1)[0];
    let lastNameB = playerB.split(" ").slice(-1)[0];

    // Compare last names for descending order
    if (lastNameA < lastNameB) return 1;
    if (lastNameA > lastNameB) return -1;
    return 0;
  });

  return playersCopy;
}

// Function gets the 12th player in a sorted list
function getTwelfthPlayer(sortedList) {
  if (sortedList.length >= 12) {
    return sortedList[11]; 
  } else {
    return "There are less than 12 players in the list.";
  }
}

// Run all functions and display results on HTML 
document.getElementById("intersection").textContent =
  findPlayersOnBothRosters(giants40ManRoster, giantsActiveRoster).join(", ");

document.getElementById("unique40man").textContent =
  findPlayersOnlyIn40ManRoster(giants40ManRoster, giantsActiveRoster).join(", ");

document.getElementById("uniqueCount").textContent =
  countTotalUniquePlayers(giants40ManRoster, giantsActiveRoster);

let sortedActivePlayers = sortPlayersByLastNameDescending(giantsActiveRoster);

document.getElementById("sortedActive").textContent = sortedActivePlayers.join(", ");

document.getElementById("twelfthPlayer").textContent = getTwelfthPlayer(sortedActivePlayers);
