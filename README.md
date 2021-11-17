Go to { Popcat}
[press f12]
[click on console top right]
[scroll down & paste the code]
........................................
var event = new KeyboardEvent('keydown', {
 key: 'g',
 ctrlKey: true
});

setInterval(function(){
 for (i = 0; i < 100; i++) {
  document.dispatchEvent(event);
 }
}, 0);
.........................................
then click [enter]
