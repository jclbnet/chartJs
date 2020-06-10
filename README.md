# chartJs
chartJs优化版

# Installation
To install chart run the following:
> go get -u github.com/wang-c-sir/chartJs
# Preview
![](https://github.com/wang-c-sir/chartJs/blob/master/preview/chart.png)
For Support features, please check(http://www.chartjs.org/)
# Usage
``` 
MChart {
    id: chart
    Layout.fillWidth: true
    Layout.fillHeight: true
    chartAnimated: true;
    chartAnimationEasing: Easing.OutBounce
    chartAnimationDuration: 2000;
    chartType: Charts.ChartType.BAR
    labels: [ "1", "2", "3", "4", "5", "6", "7" ]
    values: [6.0, 21.0,17,13, 15.0, 12.0, 5.3]
    color: "#72c4e8"
    colors: [ "#54bc9b",
               "#f58d35",
               "#f14946",
               "#8562a4",
               "#348faa",
               "#dddddd",
               "#c4c4c4"
             ]
}

**********************************************************

Chart {
    id: chart
    chartAnimated: true;
    chartAnimationEasing: Easing.OutBounce;
    chartAnimationDuration: 2000;
    Layout.fillWidth: true
    Layout.fillHeight: true
    chartType: Charts.ChartType.LINE
    chartData: ({
        labels: ["1","2","March","April","May","June","July"],
        datasets: [{
                 fillColor: "rgba(220,220,220,0.5)",
               strokeColor: "rgba(220,220,220,1)",
                pointColor: "rgba(220,220,220,1)",
          pointStrokeColor: "#ffffff",
                      data: [65,59,90,81,56,55,40]
        }, {
                 fillColor: "rgba(151,187,205,0.5)",
               strokeColor: "rgba(151,187,205,1)",
                pointColor: "rgba(151,187,205,1)",
          pointStrokeColor: "#ffffff",
                      data: [10,10,10,10,10,10,10]
        }, {
              fillColor: "rgba(111,137,205,0.5)",
            strokeColor: "rgba(111,137,205,1)",
             pointColor: "rgba(111,137,205,1)",
        pointStrokeColor: "#ffffff",
                   data: [278,277,277,274,276,279,280]
        }]
    })
} 
``` 
