To fetch data from an api, handle promises using either .then or async await.
Get the data as soon as the page loads, use useEffect and store the data in a state using UseState.
The link for the GET api is [API](https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=10&page=1&sparkline=false)
This will return an array of 10 objects, each containing a name,id,image,symbol, current_price,total_volume.
Create a component for table row in a separate file and pass the object as a prop in that file.
Render the ui as shown in the image. Use map to map that table row and put it inside a table object.
Also give keys while mapping.
