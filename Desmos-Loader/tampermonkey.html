// ==UserScript==
// @name         Embeddable Desmos
// @namespace    http://tampermonkey.net/
// @version      0.5
// @description  Teachers cannot tell you are cheating when you use this script to embed Desmos on your math quiz:) Search using input and button. Hide popup with right arrow key!
// @author       H3LLF1R3
// @match        https://canvas.instructure.com/courses/*
// @grant        none
// ==/UserScript==

function addit(){

document.body.innerHTML += `
<p style="z-index:1000; font-size:0.5em; position:fixed; right:0; bottom:0;">AU=Resize; AD=LoadIt; AR=Hide; AL=NewSrc;</p>
<div class="resizer" id="cont" style="display:flex; margin:0; padding:0; resize:both; overflow:hidden; position:fixed; z-index:1000; left:0; top:0; width:20%; height:30%;">
<iframe id="desmos" class="resized" src="https://www.desmos.com/calculator" style="flex-grow:1; margin:0; padding:0; border:0; display:flex;"></iframe>
</div>
 `

}

document.addEventListener('keyup', function(event){
 if (event.code == 'ArrowDown'){
  addit();
 }
 if (event.code == 'ArrowRight'){
    if (document.getElementById('cont').style.display == 'none'){
        document.getElementById('cont').style.display='flex';
    }else if (document.getElementById('cont').style.display == 'flex'){
        document.getElementById('cont').style.display='none';
    }
 }
 if (event.code == 'ArrowUp'){
    document.getElementById('cont').style.width='20%';
    document.getElementById('cont').style.height='30%';
 }
 if (event.code == 'ArrowLeft'){
    var newSrc = prompt('Enter a new source (Valid URL)');
    document.getElementById('desmos').src=newSrc;
 }

});
