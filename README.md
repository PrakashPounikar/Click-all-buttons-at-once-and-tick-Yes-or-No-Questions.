// # Click-all-buttons-at-once-and-tick-Yes-or-No-Questions.
// It will find all radio button hidden in specific class to auto click them at once and after than we need to provide ID's of a group to be selected what questions to be answered from our side. It will // find and tick mark them according to our choosen answer type Yes or No.



var buttons = document.getElementsByClassName('toggle-btn');
for(var i = 0; i < buttons.length; i++)  
     buttons[i].click();

var group = document.getElementById('group2');

var buttons = group.querySelectorAll('input[type="radio"][value="No"]');
for (var i = 0; i < buttons.length; i++) {
  buttons[i].click();
}
