Download Link: https://assignmentchef.com/product/solved-cs220-lab5-machine-language-basics
<br>
<strong>Translate the following into Assembly Instructions: </strong>

<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>1)</strong> <strong>Set RAM[0] to 3 </strong><strong>Set RAM[1] to 5 </strong><strong>Set RAM[2] to 1 </strong><strong>Set RAM[3] to -1 </strong></td>

   <td width="312"> @3D = A @0M = D @5D = A@1M = D @2M = 1@3M = -1</td>

  </tr>

  <tr>

   <td width="312"><strong>2)</strong> <strong>Set RAM[0] to 2 </strong><strong>Set RAM[1] to 3 </strong><strong>Set RAM[2] = RAM[0] + RAM[1] </strong></td>

   <td width="312"></td>

  </tr>

  <tr>

   <td width="312"><strong>3)</strong>  Set <strong>D </strong>to <strong>A – 1 </strong></td>

   <td width="312"></td>

  </tr>

  <tr>

   <td width="312"><strong>4)</strong> Set both <strong>A </strong>and <strong>D </strong>to <strong>A + 1 </strong></td>

   <td width="312"></td>

  </tr>

  <tr>

   <td width="312"><strong>5)</strong> Set <strong>D </strong>to <strong>19 </strong></td>

   <td width="312"></td>

  </tr>

 </tbody>

</table>




<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>6)</strong> Set both <strong>A </strong>and <strong>D </strong>to <strong>A + D </strong></td>

   <td width="312"></td>

  </tr>

  <tr>

   <td width="312"><strong>7)</strong> Set <strong>RAM[5034] </strong>to <strong>D – 1 </strong></td>

   <td width="312"></td>

  </tr>

  <tr>

   <td width="312"><strong>8)</strong> Set <strong>RAM[543] </strong>to <strong>171 </strong></td>

   <td width="312"></td>

  </tr>

  <tr>

   <td width="312"><strong>9)</strong> Increment<strong> RAM[7]</strong>by <strong>1</strong> and store result in <strong>D </strong></td>

   <td width="312"></td>

  </tr>

  <tr>

   <td width="312">  <strong>10)</strong><strong>    </strong>Increment <strong>RAM[12]</strong>by <strong>3</strong> and store result in <strong>D </strong></td>

   <td width="312"></td>

  </tr>

  <tr>

   <td width="312"><strong>11)</strong> // Convert the following Java code to assembly<strong> int i = 5; i++; i+=2; i-=3; </strong></td>

   <td width="312"></td>

  </tr>

  <tr>

   <td width="312">12) // Convert the following Java code to assembly<strong> int i = 5; int j = 10; int k = i </strong><strong>–</strong><strong> j;</strong></td>

   <td width="312"></td>

  </tr>

 </tbody>

</table>

<h2>Translate the following tasks into Assembly Instructions</h2>

<table width="677">

 <tbody>

  <tr>

   <td width="263">1) <strong>sum = 0 </strong></td>

   <td width="414"></td>

  </tr>

  <tr>

   <td width="263">2) <strong>j = j + 1 </strong></td>

   <td width="414"></td>

  </tr>

  <tr>

   <td width="263">3) <strong>q = sum + 12 – j </strong></td>

   <td width="414"></td>

  </tr>

  <tr>

   <td width="263">4) // Declare that arr=100 and n =10<strong> </strong><strong>int n = 10; </strong><strong>int[] arr = new int[n]; arr[3] = -1 </strong></td>

   <td width="414"></td>

  </tr>

  <tr>

   <td width="263">5) // Assume that j has already been declared<strong>arr[j] = 0 </strong></td>

   <td width="414"></td>

  </tr>

  <tr>

   <td width="263">6) <strong>arr[j] = 17 </strong></td>

   <td width="414"></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<h1>Lab #5 – Machine Language Jumps</h1>




<h2>Translate the following instructions into Assembly Instructions</h2>

<table width="647">

 <tbody>

  <tr>

   <td width="212">1) <strong>goto 50 </strong></td>

   <td width="435"></td>

  </tr>

  <tr>

   <td width="212">2) <strong>if D==0 goto 112 </strong></td>

   <td width="435"></td>

  </tr>

  <tr>

   <td width="212">3) <strong>if D&lt;9 goto 507 </strong></td>

   <td width="435"></td>

  </tr>

  <tr>

   <td width="212">4) <strong>if RAM[12]&gt;0 goto 50 </strong></td>

   <td width="435"></td>

  </tr>

  <tr>

   <td width="212">5) <strong>if sum&gt;0 goto END </strong></td>

   <td width="435"></td>

  </tr>

  <tr>

   <td width="212">6) <strong>if x[i]&lt;=0 goto NEXT </strong></td>

   <td width="435"></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<h1>Lab #5 – Machine Language Loops</h1>

<strong> </strong>




<h2>Translate the following instructions into Assembly Instructions</h2>

<table width="647">

 <tbody>

  <tr>

   <td width="239">1) <strong> </strong><strong>int n = 5; </strong><strong>for (int i=1;i&lt;=n;i++) {} </strong></td>

   <td width="408"></td>

  </tr>

  <tr>

   <td width="239">2)<strong>int sum = 0; int n = 5; </strong><strong>for (int i=1;i&lt;=n;i++) {   sum += i; </strong><strong>} </strong></td>

   <td width="408">                           </td>

  </tr>

  <tr>

   <td width="239">3)<strong>// Declare an arr at RAM[20] </strong><strong>// Size (n) of 10 for (int i=0; i&lt;n; i++)    arr[i] = -1; </strong></td>

   <td width="408"></td>

  </tr>

  <tr>

   <td width="239">4)<strong>// Declare an arr at RAM[20] </strong><strong>// Size (n) of 5 for (int i=0; i&lt;n; i++)    arr[i] = 100; </strong></td>

   <td width="408">                             </td>

  </tr>

 </tbody>

</table>

<strong> </strong>