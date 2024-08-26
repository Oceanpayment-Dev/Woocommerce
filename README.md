<h2>Overview</h4>
<div style="color:red">
Klarna transaction status response code description:
<ol>
    <li>Success status: payment_details = 80000 and payment_status = -1 (pre-authorization status, authorization or withdrawal can be performed through the pre-auth function). Orders that need to be shipped can be authorized first, and authorization will be revoked if they are not shipped;</li>
   <li>Pending non-pre-authorization status: payment_details = 80003 and payment_status = -1, (enter Klarna risk control, the payment result can be changed to success or failure for a maximum of 24 hours);</li>
   <li>Failure status: payment_details = 80072, payment_status = 0.</li>
</ol>
</div>
<h2>WordPress plugin, support the latest version.</h2>
<h4>Introduce</h4>
WordPress is a website creation tool and content management system based on the PHP programming language, and many websites run on it. Its extensible template and plug-in framework enable WordPress site owners to integrate OP for accepting payments quickly.
<ul>
  <li>Supports Card Payments and Alternative Payments embedded plug-ins.</li>
  <li>Support the latest version of Woocommerce.</li>
</ul>
<h4>Plug-in installation</h4>
<ol>
    <li>Upload the Oceanpayment-klarna.zip plug-in in the WordPrwss background.</li>
    <li>Activate oceanpayment klarna in the plugin menu.</li>
    <li>Click on woocommerce and select payment settings.</li>
    <li>Fill in the configuration information.</li>
</ol>
<table>
  <tr>
    <th>Configuration</th>
    <th>Options/values</th>  
  </tr>
  <tr>
    <td>Enable/Disable</td>
    <td>Configure whether to enable the payment option, unchecked to not enable payment.</td>
  </tr>
  <tr>
    <td>Title</td>
    <td>Klarna</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Optional value, description of the payment method in the shop front, usually located below the payment method name.</td>
  </tr>
  <tr>
    <td>Account</td>
    <td>Provide by Oceanpayment technical support.</td>
  </tr>
  <tr>
    <td>Terminal</td>
    <td>Provide by Oceanpayment technical support.</td>
  </tr>
  <tr>
    <td>SecureCode</td>
    <td>Provide by Oceanpayment technical support.</td>
  </tr>
  <tr>
    <td>Submiturl</td>
    <td>Production:production environment;Sandbox:Test environment.</td>
  </tr>
    <tr>
    <td>Write The Logs</td>
    <td>True/False.</td>
  </tr>
</table>
