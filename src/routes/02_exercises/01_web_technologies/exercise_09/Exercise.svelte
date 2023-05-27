<script> 
const radius = 5;

function circumference_circle_1(r) {
    return (2*Math.PI*r).toFixed(2)
};

const circumference_circle_2 = (r) =>  {
    return (2*Math.PI*r).toFixed(2)
}

</script> 

<body> The circumference of a circle with radius {radius} m is {circumference_circle_1(radius)} m.
This should be {circumference_circle_2(radius)} m.
</body>