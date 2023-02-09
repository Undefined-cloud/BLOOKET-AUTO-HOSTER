# BLOOKET-AUTO-HOSTER
STEPS:
1: DOWNLOAD THIS EXTENSION: https://chrome.google.com/webstore/detail/scripty-javascript-inject/milkbiaeapddfnpenedfgbfdacpbcbam and then go to https://scripty.abhisheksatre.com/ and then add a script


2: insert this script:
setInterval(function() {
if (window.location.href === "https://goldquest.blooket.com/host/gold/final") {
setTimeout(function() {
if (window.location.href === "https://goldquest.blooket.com/host/gold/final") {
window.location.href = "https://goldquest.blooket.com/host/settings?gid=63e45eccb763dda456a255ec";
}
}, 10000);
} else if (window.location.href !== "https://goldquest.blooket.com/host/settings?gid=63e45eccb763dda456a255ec" &&
window.location.href !== "https://goldquest.blooket.com/host/join" &&
window.location.href !== "https://goldquest.blooket.com/host/gold" &&
window.location.href !== "https://goldquest.blooket.com/host/gold/instructions") {
window.location.href = "https://goldquest.blooket.com/host/settings?gid=63e45eccb763dda456a255ec";
}
let hostButton = document.querySelector(".styles__hostButton___3ZLLE-camelCase");
if (hostButton) {
hostButton.click();
}
setTimeout(function() {
if (window.location.href === "https://goldquest.blooket.com/host/join") {
console.log("Successfully redirected to https://goldquest.blooket.com/host/join");
let startButton = document.querySelector(".styles__startButton___IT3dp-camelCase");
if (startButton) {
setTimeout(function() {
startButton.click();
}, 50000);
}
} else {
console.error("Failed to redirect to https://goldquest.blooket.com/host/join");
}
}, 5000);
}, 10000);

after you do that, click on automaticly and then click save, then youre blooket game will auto host and to turn of the auto hoster, just turn off the extension!
