
# Draggable
 Quickly make any element scrollable on touch with just one line of code.
 You just need jquery

 Example :

<pre><code>
	<html>
	  <div id='enhanced'>
	  
	  </div>
	</html>
</code></pre>
<style>
            #enhanced {
                 padding: 30px 30px 15px 30px;
          	     overflow:auto;/* this adds horizontal scroll*/
          	     background-color: #000;
          	     cursor: pointer;
          	     margin-bottom: 30px;
          	     width:90%;
          	     height:500px;
	          }
</style>



<script>
      $('#timeline').attachDragger();
</script>


