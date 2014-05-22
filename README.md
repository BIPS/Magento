Copyright (C) 2012-2014 by BIPS

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

About
=====
+ Bitcoin payments via BIPS for Magento.
+ Version 0.1
	
System Requirements:
===================
+ BIPS API, Merchant Secret
+ Curl PHP Extension
+ JSON Encode
  
Configuration Instructions:
==========================
    1. Upload files to your Magento installation.
    2. Go to your Magento administration. System -> Configuration then Payment Methods, in the left menu. You may need to clear the store cache before BIPS shows up.
    3. In BIPS Merchant IPN Callback URL, enter this link http://YOUR_MAGENTO_URL/index.php/BIPS_callback/
    4. Enter a strong IPN secret just below.
    5. In module settings "API key" <- set your BIPS API key.
    6. In module settings "IPN secret" <- set your BIPS IPN secret.

    (optional) On-site Payment. Set to "Yes" to embed payment in the checkout page. Set to "No" for redirecting to BIPS to complete payment.

### Tested with:

+ Magento