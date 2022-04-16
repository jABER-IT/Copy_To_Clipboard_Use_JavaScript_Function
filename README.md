# Copy_To_Clipboard_Use_JavaScript_Function
Copy To_Clipboard Use JavaScript Function </br>
Github Pages URL- https://jaber-it.github.io/Copy_To_Clipboard_Use_JavaScript_Function/ </br></br></br>


<img src="https://github.com/jABER-IT/Copy_To_Clipboard_Use_JavaScript_Function/blob/main/Copy%20To%20Clipboard%20Finial%20Code%202.PNG"/>


<div class="K2_CBox">
		<div class="CB_Heading">
			<span>Paste The Following Code</span> <button class="C_box_main" type="button"><i class="CBox_icn"></i></button>
		</div>`
		<div class="textCopy">
<pre class="prettyprint lang-scm highlight" style="position:relative;padding: 10px 0px 10px 30px;background:#13052e;display:block;direction:ltr;unicode-bidi:bidi-override;color:#fff;word-break:normal;border:none;border-left:7px solid #F9BC00;background-color:#13052e;border-radius:8px"><code style="font-size:14px;line-height: 1.3;white-space:pre-wrap">
        function get_api_data() {
            var xhr = new XMLHttpRequest();
                 $s('P96_JSON',(xhr.responseText));
                 }
        xhr.send();
}</code></pre></div></div>

<div class="K2_CBox">
		<div class="CB_Heading">
			<span>Paste The Following Code</span> <button class="C_box_main" type="button"><i class="CBox_icn"></i></button>
		</div>`
		<div class="textCopy">
<pre class="prettyprint lang-scm highlight" style="position:relative;padding: 10px 0px 10px 30px;background:#13052e;display:block;direction:ltr;unicode-bidi:bidi-override;color:#fff;word-break:normal;border:none;border-left:7px solid #F9BC00;background-color:#13052e;border-radius:8px"><code style="font-size:14px;line-height: 1.3;white-space:pre-wrap">
function addCopyButtons(clipboard) {
          document.querySelectorAll("pre &gt; code").forEach(function(codeBlock) {
              BtnEle = document.querySelector(".C_box_main");
              BtnEle.addEventListener("click", function() {
                     console.log('Text Copy')
                  }, function(error) {
                      console.error(error)
                  })
              });
</code></pre></div></div>

<div class="K2_CBox">
		<div class="CB_Heading">
			<span>Paste The Following Code</span> <button class="C_box_main" type="button"><i class="CBox_icn"></i></button>
		</div>`
		<div class="textCopy">
<pre class="prettyprint lang-scm highlight" style="position:relative;padding: 10px 0px 10px 30px;background:#13052e;display:block;direction:ltr;unicode-bidi:bidi-override;color:#fff;word-break:normal;border:none;border-left:7px solid #F9BC00;background-color:#13052e;border-radius:8px"><code style="font-size:14px;line-height: 1.3;white-space:pre-wrap">

    if (navigator && navigator.clipboard) {
          addCopyButtons(navigator.clipboard)
       } else {
          var script = document.createElement("script");
          script.onload = function() {
              addCopyButtons(clipboard)
          };
          document.body.appendChild(script)
       }
</code></pre></div></div>
