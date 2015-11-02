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

//Comments

//console.log('ScrollY: ' + event);
// var headerStyle = {
//   height: 200,
//   flexDirection: 'row',

//Variables

var toolbar
var styles = StyleSheet.create({
var precomputeStyle = require('precomputeStyle');

//Operators

var reqUrl = BASE_URL + this.props.story.id;
var scrollY = -event / PIXELRATIO;

//Arithmetic

