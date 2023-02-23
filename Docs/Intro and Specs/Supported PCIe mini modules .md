<p>Turing Pi 2 Board has two Mini PCIe slots connected to Node1 and Node2. These are standard Mini PCIe connectors, and any extension card that is supported by the Linux Kernel should work.</p>
<p> </p>
<p><strong>The Node1</strong> slot is connected to the Mini PCIe that also has a built-in <strong>GSM SIM cardholder, </strong>this will work in concert with GSM modems that use the Mini PCIe slot.</p>
<p> </p>
<h2>List of tested Mini PCIe cards</h2>
<p>Here, we would like to post Mini PCIe cards that are verified to work. If you have tried and got a working PCIe card, feel free to post the model and type in the comments, and we will add them to the list.</p>
<p> </p>
<table style="border-collapse: collapse; width: 100%;" border="1">
<tbody>
<tr>
<td class="wysiwyg-text-align-center" rowspan=2>Vendor</td>
<td class="wysiwyg-text-align-center" rowspan=2><strong>Type</strong></td>
<td class="wysiwyg-text-align-center" colspan=3><strong>Working?</strong></td>
<td class="wysiwyg-text-align-center" rowspan=2><strong>Comments</strong></td>
</tr>
<tr>
<td class="wysiwyg-text-align-center"><strong>Jetson</strong></td>
<td class="wysiwyg-text-align-center"><strong>CM4 / RPi OS</strong></td>
<td class="wysiwyg-text-align-center"><strong>Other?</strong></td>
</tr>
<tr>
  <td>InLine 66905</td>
  <td>USB 3.0 controller</td>
  <td>Yes</td>
  <td>Yes</td>
  <td>N/A</td>
  <td>Required the middle standoff desoldering. Based on Reneseas D720202 chip</td>
</tr>
<tr>
  <td>NFHK NF-SA-033</td>
  <td>SATA controller</td>
  <td>Yes</td>
  <td>Yes</td>
  <td>N/A</td>
  <td>Based on the ASM1061 chip</td>
</tr>
</tbody>
</table>
