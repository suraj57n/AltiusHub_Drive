approact: 1.use contextProvider to avoid contest drilling in all componets
2.create class for all Interfaces and use createcontext hook to share data with all the componets
3.Make an array of InvoiceItem array where all the items to share will be stored
4.share that array through contextProvder with the whole page
5.make a home page with toolbar and sidebar where an component of invoice is displaye the whole data in table format invoice component=>
1.display the array in the form of table here
2.use event listener to listen to tap on any of the table row and access that row using the index number from the array and use that to grant access to the user to change data in the table
3.a button for save changes option which gets out of the page and displays the new updated data
4.a button for add data option which shows an empty table with all the required fields of the invoice to add data and when its done adding the data the pages gets updated with the new data using useEffect hook
