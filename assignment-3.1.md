Tyler Thomas
StoryScreen.js
//Syntax


var React = require('react-native');
var precomputeStyle = require('precomputeStyle');
var BASE_URL = 'http://news.at.zhihu.com/api/4/news/';

//Statement

var StoryScreen = React.createClass({
  componentDidMount: function() {
    this.fetchStroyDetail();
onWebViewScroll: function(event) {

//Comment
//console.log('ScrollY: ' + event);
// var headerStyle = {
//   height: 200,
//   flexDirection: 'row',