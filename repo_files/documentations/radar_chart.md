# RadarChart
<img src="https://github.com/imaNNeoFighT/fl_chart/raw/master/repo_files/images/radar_chart/radar_chart_sample_1.jpg" width="300" >

### How to use
```dart
RadarChart(
  RadarChartData(
    // read about it in the below section
  ),
);
```

### RadarChartData
|PropName		|Description	|default value|
|:---------------|:---------------|:-------|
|dataSets| list of [RadarDataSet ](#RadarDataSet) that is shown on the radar chart|[]|
|radarBackgroundColor| This property fills the background of the radar with the specified color.| Colors.transparent|
|radarBorderData| shows a border for radar chart|BorderSide(color: Colors.black, width: 2)|
