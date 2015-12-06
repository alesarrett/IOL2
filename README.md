# IOL2
Project related to the Institute of Open Leadership 2: https://openpolicynetwork.org/iol/

<script src="http://d3js.org/d3.v3.min.js" charset="utf-8"></script>
<script src="http://cdnjs.cloudflare.com/ajax/libs/topojson/1.6.9/topojson.min.js"></script>
<script src="./datamaps.world.min.js"></script>
<script>
    var map = new Datamap({
      element: document.getElementById('container'),
      fills: {
        defaultFill: "#ABDDA4",
        IOL2fellows: "#fa0fa0"
      },
      data: {
        NGA: { fillKey: "IOL2fellows" },
        CAN: { fillKey: "IOL2fellows" },
        ITA: { fillKey: "IOL2fellows" },
        TUN: { fillKey: "IOL2fellows" },
        NLD: { fillKey: "IOL2fellows" },
        NZL: { fillKey: "IOL2fellows" },
        BGD: { fillKey: "IOL2fellows" },
        NPL: { fillKey: "IOL2fellows" },
        UGA: { fillKey: "IOL2fellows" },
        ZAF: { fillKey: "IOL2fellows" },
        AUT: { fillKey: "IOL2fellows" },
        KEN: { fillKey: "IOL2fellows" },
        BRA: { fillKey: "IOL2fellows" },
        RWA: { fillKey: "IOL2fellows" },
        USA: { fillKey: "IOL2fellows" },
      }
    });
</script>
