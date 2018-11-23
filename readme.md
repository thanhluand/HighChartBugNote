error cannot update serrial and update chart as same time
c.chart.update({
  chart: {
    type: this.selected.type
  }
}, false);

c.chart.series[0].setData([{x: 1, y: 10}, {x: 2, y: 20}, {x: 3, y: 32}, {x: 4, y: 25}, {x: 5, y: 23}, {x: 6, y: 27}, {x: 7, y: 13}, {x: 8, y: 14}, {x: 9, y: 26}, {x: 10, y: 21}]);
