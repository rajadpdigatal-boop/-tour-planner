<!DOCTYPE html>
<html>
<head>
    <title>Tour Planner</title>
</head>
<body>

<h1>🌍 Tour Planner App</h1>

<input id="place" placeholder="Enter city">
<button onclick="search()">Search</button>

<p id="result"></p>

<script>
function search(){
    let place =
    document.getElementById("place").value;

    document.getElementById("result").innerText =
    "You searched: " + place;
}
</script>

</body>
</html>
