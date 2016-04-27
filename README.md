<img src="PayU-Logo.png" align="right" />
# Tokenization JavaScript


Introduction
--------------------------------------
With the Tokenization Javascript you can create a form that allows you to capture the credit card data from your clients on your website, securely and without the need to store the data on your system. The javascript will connect directly with the PayU system, which will tokenize the data and return the token assigned to the credit card on file.

<i>Tokenization is available for Brazil, Colombia, Mexico, Argentina, Panama and Peru </i>

Description
--------------------------------------
Examples in each language using the Tokenization JavaScript


Take in count
--------------------------------------
<b>Urls of the environments</b><br>
Production
```bash
payU.setURL('https://api.payulatam.com/payments-api/4.0/service');
```
Sandbox
```bash
payU.setURL('http://sandbox.api.payulatam.com/payments-api/4.0/service');
```
<br>

<b>Sandbox Credentials</b>
<table >
	<tr>
		<td><span style="color: #fff"><b>Public Key</span></td>
		<td><span style="color: #fff"><b>accountId</span></td>
		<td><span style="color: #fff"><b>Country</span></td>
	</tr>
	<tr>
		<td rowspan="6">PKaC6H4cEDJD919n705L544kSU</td>
		<td>512322</td>
		<td>Argentina</td>
	</tr>
	<tr>
		<td>512321</td>
		<td>Colombia</td>
	</tr>
	<tr>
		<td>512324</td>
		<td>México</td>
	</tr>
	<tr>
		<td>512326</td>
		<td>Panamá</td>
	</tr>
	<tr>
		<td>512323</td>
		<td>Perú</td>
	</tr>
	<tr>
		<td>512323</td>
		<td>Brazil</td>
	</tr>
</table>

License
--------------------------------------
Copyright (c) 2016 PayU Latam

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
