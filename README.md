example reference

<body>
  <script>
    const dataset = [21, 13, 44, 71, 25, 18, 8, 14, 2];
    
    const w = 555;
    const h = 111;
    
    const svg = d3.select("body")
                  .append("svg")
                  .attr("width", w)
                  .attr("height", h);
    
    svg.selectAll("rect")
       .data(dataset)
       .enter()
       .append("rect")
       .attr("x", (d, i) => i * 30)
       .attr("y", (d, i) => {
          /*
            fill in with code to invert
          */
       })
       .attr("width", 25)
       .attr("height", (d, i) => 3 * d);
  </script>
</body>
