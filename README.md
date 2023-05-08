Download Link: https://assignmentchef.com/product/solved-syd366-homework2-inventory-test
<br>
<strong><u>Case Study</u></strong>

Margaret Poku runs <em>Auto Supplies Ltd</em>, a small company that supplies aftermarket auto mobile parts to local garages.

Margaret employs a small team, including some office, sales, and warehouse staff.  A few times a year, Margaret attends trade shows and visits manufacturers to learn about new products.   Margaret uses an outside delivery service to deliver orders to her clients.

Your company has been hired to started looking at Margaret’s inventory records and found that Margaret records weights and measures for each of the products that she stocks, for proper arrangement in her warehouse and to assist in quick calculation of shipment costs.  Margaret orders product from various suppliers through their online ordering portals and must record her purchases so that she knows what she has purchased and what has arrived to be stock in her warehouse.

Your team leader has written the following scenarios to capture Margaret’s requirements.

<table>

 <tbody>

  <tr>

   <td width="125">Use Case Name</td>

   <td colspan="3" width="498">Create Product Information</td>

  </tr>

  <tr>

   <td width="125">Triggering Event</td>

   <td colspan="3" width="498">A new product of interest to the business</td>

  </tr>

  <tr>

   <td width="125">Brief Description</td>

   <td colspan="3" width="498">Allows the Owner to record a new product.</td>

  </tr>

  <tr>

   <td width="125">Actors</td>

   <td colspan="3" width="498">Owner</td>

  </tr>

  <tr>

   <td width="125">Related Use Cases</td>

   <td colspan="3" width="498"> </td>

  </tr>

  <tr>

   <td width="125">Preconditions</td>

   <td colspan="3" width="498">Owner has opened the Main Menu.</td>

  </tr>

  <tr>

   <td width="125">Post Conditions</td>

   <td colspan="3" width="498">Product is saved to the database and now can be purchased or used in a service.</td>

  </tr>

  <tr>

   <td width="125">Flow of activities</td>

   <td colspan="2" width="252">Actor</td>

   <td width="246">System</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">1.</td>

   <td width="222">Requests to add a new product</td>

   <td width="246">Displays a list of products currently recorded in the system and prompts to add a new product.</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">2.</td>

   <td width="222">Enters the product name, description, weight, height, width, and depth of the new product.</td>

   <td width="246">Verifies that all the data is entered.  Displays the newly created product and requests to save.</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">3.</td>

   <td width="222">Request to save</td>

   <td width="246">Saves the product and returns to the main menu</td>

  </tr>

  <tr>

   <td width="125">Exception Conditions</td>

   <td colspan="3" width="498">·         Owner chooses to cancel adding the product</td>

  </tr>

 </tbody>

</table>







<table>

 <tbody>

  <tr>

   <td width="124">Use Case Name</td>

   <td colspan="3" width="499">Create Purchase</td>

  </tr>

  <tr>

   <td width="124">Triggering Event</td>

   <td colspan="3" width="499">Purchase of a product.</td>

  </tr>

  <tr>

   <td width="124">Brief Description</td>

   <td colspan="3" width="499">Allows the Owner to record a new purchase.</td>

  </tr>

  <tr>

   <td width="124">Actors</td>

   <td colspan="3" width="499">Owner</td>

  </tr>

  <tr>

   <td width="124">Related Use Cases</td>

   <td colspan="3" width="499"> </td>

  </tr>

  <tr>

   <td width="124">Preconditions</td>

   <td colspan="3" width="499">Owner has opened the Main Menu.</td>

  </tr>

  <tr>

   <td width="124">Post Conditions</td>

   <td colspan="3" width="499">Purchase is saved to the database and now can be queried.</td>

  </tr>

  <tr>

   <td width="124">Flow of activities</td>

   <td colspan="2" width="258">Actor</td>

   <td width="241">System</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="41">1.</td>

   <td width="217">Requests to add a new purchase</td>

   <td width="241">Displays a list of suppliers and prompts for selection.</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="41">2.</td>

   <td width="217">Selects a supplier.</td>

   <td width="241">Verifies that a supplier was selected.  Prompts for purchase date and selection of receipt file location.</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="41">3.</td>

   <td width="217">Enters purchase date and receipt file selected.</td>

   <td width="241">Verifies that date was entered, and receipt selected.Creates a unique identifier for the purchase.   Prompts to enter product details.</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="41">loop</td>

   <td width="217">Chooses new detail</td>

   <td width="241">Displays a list of products and prompts for selection.  Prompts for price, quantity ordered,  and quantity received</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="41">4.</td>

   <td width="217">Selects a product and enters price and quantity.</td>

   <td width="241">Product must be selected.Price and quantity must be entered Weight of the purchase is calculated.Displays purchase including weight, date and list of products. Prompts to add another product</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="41">End</td>

   <td width="217">When all products selected</td>

   <td width="241">Displays purchase including weight, date and list of products. Verifies that at least one product has been selected. Prompts to save purchase</td>

  </tr>

  <tr>

   <td width="124"> </td>

   <td width="41">5.</td>

   <td width="217">Chooses to save</td>

   <td width="241">Saves the purchase and returns to the main menu</td>

  </tr>

  <tr>

   <td width="124">Exception Conditions</td>

   <td colspan="3" width="499">·         Owner chooses to cancel adding the purchase</td>

  </tr>

 </tbody>

</table>

<strong><u>Question 1</u></strong>

Complete a detailed <strong>class diagram</strong> (minimum 7-15 classes) to support what your team has learned so far about <em>Auto Supplies Ltd.  </em>

<ul>

 <li>Your class diagram must show the following:

  <ul>

   <li>Classes, attributes (including all reference attributes)</li>

   <li>Associations, multiplicities, and association names</li>

  </ul></li>

</ul>

<strong><u>Question 2</u></strong><u> </u>

Complete <strong>Object Level Sequence Diagrams</strong> to support the above scenarios. You are to use the appropriate UML annotations to for your model.

<strong><u>Question 3</u></strong><u> </u>

Margaret would like the system to suggest where to store items in the warehouse.  Different racks in her warehouse can hold different products with different heights.  How would you incorporate this change in your model?  <strong>Please describe in clear English</strong>.

<strong><u>Question 4</u></strong><u> </u>

Margaret buys a new label printer for her warehouse.  She needs to make sure that she never loses the receipt for warranty purposes.  Is the printer considered to be inventory?  How would your model change to support this requirement?

<strong><u>Question 5</u></strong><u> </u>

What is SKU?  Is this important to Margaret?

<strong><u>Question 6</u></strong><u> </u>

Margaret finds a sale on Windshield Washer Fluid and would like to buy six months’ worth of product.  How would she use your model to figure out how many to buy?

<strong><u>Question 7</u></strong><u> </u>

Margaret had an idea: What about if the system could tell her when she will start to run out of a product? How would your model change to accommodate this?