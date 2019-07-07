
/*!
 * Globalize Runtime v1.4.0 2018-07-17T20:38Z Released under the MIT license
 * http://git.io/TrdQbw
 */
"undefined"!=typeof process&&"node"===process.release.name?global.localizeGlobalNamespace=global:window.localizeGlobalNamespace=window,localizeGlobalNamespace.TabGlobalize=function(){var n=function(e,a){return e=e.replace(/{[0-9a-zA-Z-_. ]+}/g,function(e){return e=e.replace(/^{([^}]*)}$/,"$1"),"string"==typeof(r=a[e])?r:"number"==typeof r?""+r:JSON.stringify(r);var r})},o=function(e,r,a){var t;return r=e+(r?": "+n(r,a):""),(t=new Error(r)).code=e,function(){var a=arguments[0];[].slice.call(arguments,1).forEach(function(e){var r;for(r in e)a[r]=e[r]})}(t,a),t},l=function(e,r,a,t){if(!a)throw o(e,r,t)},r=function(e,r){l("E_MISSING_PARAMETER","Missing required parameter `{name}`.",void 0!==e,{name:r})},a=function(e,r,a,t){l("E_INVALID_PAR_TYPE","Invalid `{name}` parameter ({value}). {expected} expected.",a,{expected:t,name:r,value:e})},t=function(e,r){a(e,r,void 0===e||"string"==typeof e,"a string")};function i(e){if(!(this instanceof i))return new i(e);r(e,"locale"),t(e,"locale"),this._locale=e}return i.locale=function(e){return t(e,"locale"),arguments.length&&(this._locale=e),this._locale},i._createError=o,i._formatMessage=n,i._regexpEscape=function(e){return e.replace(/([.*+?^=!:${}()|\[\]\/\\])/g,"\\$1")},i._runtimeKey=function(e,r,a,t){var n,o,l;return t=t||(l=a,JSON.stringify(l,function(e,r){return r&&r.runtimeKey?r.runtimeKey:r})),0<(o=e+r+t,n=[].reduce.call(o,function(e,r){var a=r.charCodeAt(0);return 0|(e=(e<<5)-e+a)},0))?"a"+n:"b"+Math.abs(n)},i._stringPad=function(e,r,a){var t;for("string"!=typeof e&&(e=String(e)),t=e.length;t<r;t+=1)e=a?e+"0":"0"+e;return e},i._validateParameterPresence=r,i._validateParameterTypeString=t,i._validateParameterType=a,i}(),function(e,r){var a,t,n,o;a=e.TabGlobalize,t=a._runtimeKey,n=a._validateParameterType,o=function(e,r){var a;n(e,r,void 0===e||null!==(a=e)&&""+a=="[object Object]"||Array.isArray(e),"Array or Plain Object")},a._messageFormatterFn=function(r){return function(e){return"number"!=typeof e&&"string"!=typeof e||(e=[].slice.call(arguments,0)),o(e,"variables"),r(e)}},a._messageFormat={number:function(e,r){if(isNaN(e))throw new Error("'"+e+"' isn't a number.");return e-(r||0)},plural:function(e,r,a,t,n){if({}.hasOwnProperty.call(t,e))return t[e]();r&&(e-=r);var o=a(e,n);return o in t?t[o]():t.other()},select:function(e,r){return{}.hasOwnProperty.call(r,e)?r[e]():r.other()}},a._validateParameterTypeMessageVariables=o,a.messageFormatter=a.prototype.messageFormatter=function(){return a[t("messageFormatter",this._locale,[].slice.call(arguments,0))]},a.formatMessage=a.prototype.formatMessage=function(e){return this.messageFormatter(e).apply({},[].slice.call(arguments,1))}}(localizeGlobalNamespace),function(e,r){var a,t,n,o,l;a=e.TabGlobalize,t=a._runtimeKey,n=a._validateParameterPresence,o=a._validateParameterType,l=function(e,r){o(e,r,void 0===e||"number"==typeof e,"Number")},a._pluralGeneratorFn=function(r){return function(e){return n(e,"value"),l(e,"value"),r(e)}},a._validateParameterTypeNumber=l,a.plural=a.prototype.plural=function(e,r){return n(e,"value"),l(e,"value"),this.pluralGenerator(r)(e)},a.pluralGenerator=a.prototype.pluralGenerator=function(e){return e=e||{},a[t("pluralGenerator",this._locale,[e])]}}(localizeGlobalNamespace);

(function( root, factory ) {
  root.Localize = root.Localize || {};
  root.Localize.msg = new root.TabGlobalize('en');
  factory( root.TabGlobalize, root.Localize );
  if (root.Localize.initFormattersAndParsers) {
    root.Localize.initFormattersAndParsers();
  }
}(localizeGlobalNamespace, function( Globalize ) {
var validateParameterTypeNumber = Globalize._validateParameterTypeNumber;
var validateParameterPresence = Globalize._validateParameterPresence;
var pluralGeneratorFn = Globalize._pluralGeneratorFn;
var validateParameterTypeMessageVariables = Globalize._validateParameterTypeMessageVariables;
var messageFormat = Globalize._messageFormat;
var messageFormatterFn = Globalize._messageFormatterFn;

Globalize.a1662346136 = pluralGeneratorFn(function(n
/*``*/) {
  var s = String(n).split('.'), v0 = !s[1];
  return (n == 1 && v0) ? 'one' : 'other';
});
Globalize.a292632914 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: No datasource id provided"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1020264557 = messageFormatterFn((function(  ) {
  return function (d) { return "Improve performance. Choose where the join process happens when joining data from multiple sources."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1164214669 = messageFormatterFn((function(  ) {
  return function (d) { return "This workbook includes performance improvements for cross-database joins."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1213959207 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1669508057 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2133846203 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1959906570 = messageFormatterFn((function(  ) {
  return function (d) { return "Select one of the following to continue:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b817799712 = messageFormatterFn((function(  ) {
  return function (d) { return "Use database connection for cross-database joins"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1664131323 = messageFormatterFn((function(  ) {
  return function (d) { return "Data from your file connection may be moved to your live database connection. May be faster."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b564084659 = messageFormatterFn((function(  ) {
  return function (d) { return "Use this option only if the database is from a trusted source"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1812583788 = messageFormatterFn((function(  ) {
  return function (d) { return "Use Tableau for cross-database joins (default)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a871988918 = messageFormatterFn((function(  ) {
  return function (d) { return "Using the database connection for cross-database joins means that data from your file connection may be moved to your live database connection, which may be faster. Use this option only if the database is from a trusted source."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1405732433 = messageFormatterFn((function(  ) {
  return function (d) { return "Show details"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b515312374 = messageFormatterFn((function(  ) {
  return function (d) { return "Hide details"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a229986360 = messageFormatterFn((function(  ) {
  return function (d) { return "Datasource"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1871492545 = messageFormatterFn((function(  ) {
  return function (d) { return "Database Connection"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2067226219 = messageFormatterFn((function(  ) {
  return function (d) { return "File Connection"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1019335495 = messageFormatterFn((function(  ) {
  return function (d) { return "Use Tableau"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1542092929 = messageFormatterFn((function(  ) {
  return function (d) { return "Use Database Connection"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a329365055 = messageFormatterFn((function(  ) {
  return function (d) { return "average"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a266715761 = messageFormatterFn((function(  ) {
  return function (d) { return "count"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1343435155 = messageFormatterFn((function(  ) {
  return function (d) { return "sum"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1900708532 = messageFormatterFn((function(  ) {
  return function (d) { return "Analyzing Data"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1027869399 = messageFormatterFn((function(  ) {
  return function (d) { return "Explain the Mark"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1535310143 = messageFormatterFn((function(  ) {
  return function (d) { return "Explain the Mark - "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a248414582 = messageFormatterFn((function(  ) {
  return function (d) { return d.fieldCaption + " is "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1177002167 = messageFormatterFn((function(  ) {
  return function (d) { return " Possible explanations:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b233824935 = messageFormatterFn((function(  ) {
  return function (d) { return "Considering the distribution of values in the data, this value is expected to be between " + d.low + " and " + d.high + ". This takes into account the filters set on " + d.fieldCaptions + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1904875768 = messageFormatterFn((function(  ) {
  return function (d) { return "Considering the distribution of values in the data, this value is expected to be between " + d.low + " and " + d.high + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1141208204 = messageFormatterFn((function(  ) {
  return function (d) { return "Considering the distribution of values in the data, this value is expected to be between " + d.low + " and " + d.high + ". This takes into account the filter set on " + d.fieldCaption + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2145553837 = messageFormatterFn((function(  ) {
  return function (d) { return "Expected Range"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a698450905 = messageFormatterFn((function(  ) {
  return function (d) { return "Based on the selected mark, Tableau runs a statistical analysis on the data in the view and in your data source. This page shows possible explanations for the value of the selected mark, considered with other information in the data source."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a817373083 = messageFormatterFn((function(  ) {
  return function (d) { return "higher value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b432064462 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn More"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1931903763 = messageFormatterFn((function(  ) {
  return function (d) { return "lower value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1108667077 = messageFormatterFn((function(  ) {
  return function (d) { return "Average value of records"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b530273227 = messageFormatterFn((function(  ) {
  return function (d) { return d.fieldCaption + " is " + d.relativeToExpectedSum + " The average value of the records in this mark is " + d.relativeToExpectedAverage + " while the number of records contributing to this mark is " + d.relativeToExpectedCount; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1758508555 = messageFormatterFn((function(  ) {
  return function (d) { return d.fieldCaption + " is " + d.relativeToExpectedSum; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a874816807 = messageFormatterFn((function(  ) {
  return function (d) { return "Measure of Rows"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1806266771 = messageFormatterFn((function(  ) {
  return function (d) { return d.fieldCaption + " " + d.aggValue + " appears to be high, but no explanation could be found based on the available data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1053998079 = messageFormatterFn((function(  ) {
  return function (d) { return d.fieldCaption + " " + d.aggValue + " appears to be low, but no explanation could be found based on the available data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1810359573 = messageFormatterFn((function(  ) {
  return function (d) { return "Based on the data included in the data source, no explanation could be found."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1272527773 = messageFormatterFn((function(  ) {
  return function (d) { return "No explanation found in data"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1553529263 = messageFormatterFn((function(  ) {
  return function (d) { return " The fields " + d.dimensionsListString + " were considered in this analysis, but did not significantly explain the value of this mark."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a814820979 = messageFormatterFn((function(  ) {
  return function (d) { return " " + d.numberOfDimensions + " fields were considered, such as " + d.dimensionName1 + ", " + d.dimensionName2 + " and " + d.dimensionName3 + ", however analysis of this data did not significantly explain the value of this mark."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1389945084 = messageFormatterFn((function(  ) {
  return function (d) { return " Additional fields were not available for consideration in this analysis."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1774097545 = messageFormatterFn((function(  ) {
  return function (d) { return " The field " + d.dimensionName + " was considered in this analysis, but it did not significantly explain the value of this mark."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1205973716 = messageFormatterFn((function(  ) {
  return function (d) { return "Number of records"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b208960346 = messageFormatterFn((function(  ) {
  return function (d) { return d.fieldCaption + " is " + d.relativeToExpectedSum + " The number of records contributing to this mark is " + d.relativeToExpectedCount + " while the average value of the records in this mark is " + d.relativeToExpectedAverage; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1437195674 = messageFormatterFn((function(  ) {
  return function (d) { return d.fieldCaption + " is " + d.relativeToExpectedSum; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1129899480 = messageFormatterFn((function(  ) {
  return function (d) { return "Number of Rows"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1751584039 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1545851538 = messageFormatterFn((function(  ) {
  return function (d) { return "decreasing"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b674716658 = messageFormatterFn((function(  ) {
  return function (d) { return "increasing"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a771575839 = messageFormatterFn((function(  ) {
  return function (d) { return "about " + d.percentage + "% higher than expected"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a201762598 = messageFormatterFn((function(  ) {
  return function (d) { return "about " + d.percentage + "% higher than expected,"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1298767962 = messageFormatterFn((function(  ) {
  return function (d) { return "about " + d.percentage + "% higher than expected."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1549095719 = messageFormatterFn((function(  ) {
  return function (d) { return "about " + d.percentage + "% lower than expected"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1963131988 = messageFormatterFn((function(  ) {
  return function (d) { return "about " + d.percentage + "% lower than expected,"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a308976608 = messageFormatterFn((function(  ) {
  return function (d) { return "about " + d.percentage + "% lower than expected."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2052239667 = messageFormatterFn((function(  ) {
  return function (d) { return "The " + d.higherOrLowerValue + " is partially explained by the percentage of records with " + d.dimension + " = " + d.primaryValue + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1537268233 = messageFormatterFn((function(  ) {
  return function (d) { return d.fieldCaption + ":"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b752804945 = messageFormatterFn((function(  ) {
  return function (d) { return ", "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a410200647 = messageFormatterFn((function(  ) {
  return function (d) { return "A single value " + d.outlierValue + " out of " + d.numberOfRows + " rows is increasing " + d.fieldCaption + ". Excluding this value, " + d.fieldCaption + " is " + d.measureValueWithoutOutlier + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a410429365 = messageFormatterFn((function(  ) {
  return function (d) { return "A single value " + d.outlierValue + " out of " + d.numberOfRows + " rows is decreasing " + d.fieldCaption + ". Excluding this value, " + d.fieldCaption + " is " + d.measureValueWithoutOutlier + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a939957198 = messageFormatterFn((function(  ) {
  return function (d) { return "The extreme value of " + d.fieldCaption + " is " + d.outlierValueDiff + " higher than the next highest row value for the mark."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a940185916 = messageFormatterFn((function(  ) {
  return function (d) { return "The extreme value of " + d.fieldCaption + " is " + d.outlierValueDiff + " lower than the next lowest row value for the mark."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b922698114 = messageFormatterFn((function(  ) {
  return function (d) { return "Distribution of row values within " + d.fieldCaption; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b76672160 = messageFormatterFn((function(  ) {
  return function (d) { return "If this value is excluded from " + d.fieldCaption + ", " + d.fieldCaption + " is " + d.measureValueWithoutOutlier + ", which is " + d.measureValueDiff + " lower than the observed value of " + d.measureValue + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b76443442 = messageFormatterFn((function(  ) {
  return function (d) { return "If this value is excluded from " + d.fieldCaption + ", " + d.fieldCaption + " is " + d.measureValueWithoutOutlier + ", which is " + d.measureValueDiff + " higher than the observed value of " + d.measureValue + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a565007276 = messageFormatterFn((function(  ) {
  return function (d) { return "Visualize the difference"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b317944633 = messageFormatterFn((function(  ) {
  return function (d) { return "Row details"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1122061177 = messageFormatterFn((function(  ) {
  return function (d) { return "A single record with a value of " + d.outlierValue + " is increasing " + d.fieldCaption + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1121832459 = messageFormatterFn((function(  ) {
  return function (d) { return "A single record with a value of " + d.outlierValue + " is decreasing " + d.fieldCaption + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2001647515 = messageFormatterFn((function(  ) {
  return function (d) { return "A single extreme value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1209490933 = messageFormatterFn((function(  ) {
  return function (d) { return "The " + d.higherOrLowerValue + " is partially explained by " + d.dimension + " = " + d.singleValue + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b342160602 = messageFormatterFn((function(  ) {
  return function (d) { return d.fieldCaption + " " + d.aggValue + " is " + d.relativeToRange + ". The " + d.higherOrLowerValue + " is partially explained by the mix of values for " + d.dimension + ", which is not shown in this visualization."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1489957831 = messageFormatterFn((function(  ) {
  return function (d) { return "This chart shows how " + d.dimension + " contributes to the value " + d.aggValue + " of the selected mark, compared to other marks in the visualization.  Bars that extend right have a higher representation in the selected mark, whereas bars that extend left have a higher representation in the rest of the data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a869348907 = messageFormatterFn((function(  ) {
  return function (d) { return "Distribution of values"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1570395930 = messageFormatterFn((function(  ) {
  return function (d) { return "The " + d.higherOrLowerValue + " is partially explained by the mix of values for " + d.dimension + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1113059065 = messageFormatterFn((function(  ) {
  return function (d) { return "Mix of values for " + d.dimension; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1902997204 = messageFormatterFn((function(  ) {
  return function (d) { return "as expected"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b104512495 = messageFormatterFn((function(  ) {
  return function (d) { return "as expected,"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2091606043 = messageFormatterFn((function(  ) {
  return function (d) { return "as expected."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1934930482 = messageFormatterFn((function(  ) {
  return function (d) { return "higher than expected"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a391178867 = messageFormatterFn((function(  ) {
  return function (d) { return "higher than expected,"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a278169081 = messageFormatterFn((function(  ) {
  return function (d) { return "higher than expected."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1650115482 = messageFormatterFn((function(  ) {
  return function (d) { return "lower than expected"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1125737793 = messageFormatterFn((function(  ) {
  return function (d) { return "lower than expected,"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a498392877 = messageFormatterFn((function(  ) {
  return function (d) { return "lower than expected."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1518206118 = messageFormatterFn((function(  ) {
  return function (d) { return "value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b170987106 = messageFormatterFn((function(  ) {
  return function (d) { return "within the expected range"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1527213669 = messageFormatterFn((function(  ) {
  return function (d) { return "within the expected range."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a4395675 = messageFormatterFn((function(  ) {
  return function (d) { return "View Full Data"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1445791945 = messageFormatterFn((function(  ) {
  return function (d) { return "This value is within the expected range based on the all values in the data source."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a217556617 = messageFormatterFn((function(  ) {
  return function (d) { return "This value is within the expected range based on the all values in the data source."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a398661307 = messageFormatterFn((function(  ) {
  return function (d) { return "Expected value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1131194227 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit Button"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b375773432 = messageFormatterFn((function(  ) {
  return function (d) { return "Image"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2075137611 = messageFormatterFn((function(  ) {
  return function (d) { return "Choose"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b314353881 = messageFormatterFn((function(  ) {
  return function (d) { return "Choose an image..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1601228281 = messageFormatterFn((function(  ) {
  return function (d) { return "Navigate to"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1281014713 = messageFormatterFn((function(  ) {
  return function (d) { return "Dashboard Item to Show/Hide"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b35925874 = messageFormatterFn((function(  ) {
  return function (d) { return "Tooltip"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1167768531 = messageFormatterFn((function(  ) {
  return function (d) { return "Enter optional tooltip text"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b825278119 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1751365225 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a124087047 = messageFormatterFn((function(  ) {
  return function (d) { return "Apply"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1483567957 = messageFormatterFn((function(  ) {
  return function (d) { return "None"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a456387273 = messageFormatterFn((function(  ) {
  return function (d) { return "Border"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a603730507 = messageFormatterFn((function(  ) {
  return function (d) { return "Background"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1243611932 = messageFormatterFn((function(  ) {
  return function (d) { return "Opacity"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1451639454 = messageFormatterFn((function(  ) {
  return function (d) { return "%"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b561677535 = messageFormatterFn((function(  ) {
  return function (d) { return "Error"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b605462971 = messageFormatterFn((function(  ) {
  return function (d) { return "characters"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b393144260 = messageFormatterFn((function(  ) {
  return function (d) { return "Background Opacity Slider"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b45554625 = messageFormatterFn((function(  ) {
  return function (d) { return "Toggle Visual State Tabs"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1154111532 = messageFormatterFn((function(  ) {
  return function (d) { return "Format"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1484069256 = messageFormatterFn((function(  ) {
  return function (d) { return "Button Style"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a788314400 = messageFormatterFn((function(  ) {
  return function (d) { return "Image Button"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1531763702 = messageFormatterFn((function(  ) {
  return function (d) { return "Text Button"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b487156737 = messageFormatterFn((function(  ) {
  return function (d) { return "Title"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b53947005 = messageFormatterFn((function(  ) {
  return function (d) { return "Enter optional title"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a7650843 = messageFormatterFn((function(  ) {
  return function (d) { return "Button Appearance"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b419230001 = messageFormatterFn((function(  ) {
  return function (d) { return "Item Shown"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1882025923 = messageFormatterFn((function(  ) {
  return function (d) { return "Item Hidden"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1860084446 = messageFormatterFn((function(  ) {
  return function (d) { return "Font"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1495585111 = messageFormatterFn((function(  ) {
  return function (d) { return "Copy formatting to Item Hidden"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a886105561 = messageFormatterFn((function(  ) {
  return function (d) { return "Copy formatting to Item Shown"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1279838854 = messageFormatterFn((function(  ) {
  return function (d) { return "Copy"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b188525739 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1785102427 = messageFormatterFn((function(  ) {
  return function (d) { return "Certification icon"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1244229286 = messageFormatterFn((function(  ) {
  return function (d) { return "Certified by"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1758048177 = messageFormatterFn((function(  ) {
  return function (d) { return "Data connection icon"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a882984915 = messageFormatterFn((function(  ) {
  return function (d) { return "External server connection icon"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b236621279 = messageFormatterFn((function(  ) {
  return function (d) { return "File icon"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2002208184 = messageFormatterFn((function(  ) {
  return function (d) { return "Live connection"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b217021229 = messageFormatterFn((function(  ) {
  return function (d) { return "Last extract:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a888757650 = messageFormatterFn((function(  ) {
  return function (d) { return "No data connections"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1764201384 = messageFormatterFn((function(  ) {
  return function (d) { return "See more details"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1801004092 = messageFormatterFn((function(  ) {
  return function (d) { return "Tableau Server connection icon"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1055494454 = messageFormatterFn((function(  ) {
  return function (d) { return "This workbook connects to"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1718027933 = messageFormatterFn((function(  ) {
  return function (d) { return "Choose an Extension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1761576738 = messageFormatterFn((function(  ) {
  return function (d) { return "Recent Extensions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a347847875 = messageFormatterFn((function(  ) {
  return function (d) { return "No recently used extensions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1269404979 = messageFormatterFn((function(  ) {
  return function (d) { return "More..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b940322012 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more about Extensions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1768779612 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1746867806 = messageFormatterFn((function(  ) {
  return function (d) { return "Click Browse... to select an extension manifest"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1590185954 = messageFormatterFn((function(  ) {
  return function (d) { return "What are Dashboard Extensions?"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1024696899 = messageFormatterFn((function(  ) {
  return function (d) { return "Extensions are web applications that can interact with worksheets and data in Tableau. You can add custom extensions to your dashboard to add new capabilities to Tableau."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1168676373 = messageFormatterFn((function(  ) {
  return function (d) { return "Choose an Extension..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1204236182 = messageFormatterFn((function(  ) {
  return function (d) { return "Choose"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1133050893 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a775047937 = messageFormatterFn((function(  ) {
  return function (d) { return "Extensions Gallery"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b285286090 = messageFormatterFn((function(  ) {
  return function (d) { return "Selected file is too large. Select a file less than " + d.fileSize + "MB"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2012804157 = messageFormatterFn((function(  ) {
  return function (d) { return "Wrong number of files selected"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a25492626 = messageFormatterFn((function(  ) {
  return function (d) { return "File reading aborted"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a498629474 = messageFormatterFn((function(  ) {
  return function (d) { return "Find and download new extensions from the " + d.GALLERY + ". Click " + d.EXTENSIONS + " to use an extension (.trex file) from your computer."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2123682970 = messageFormatterFn((function(  ) {
  return function (d) { return "Extension Gallery"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1482451187 = messageFormatterFn((function(  ) {
  return function (d) { return "My Extensions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1985695964 = messageFormatterFn((function(  ) {
  return function (d) { return "Show template project contributors!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1376679521 = messageFormatterFn((function(  ) {
  return function (d) { return "Hide template project contributors!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1336442465 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1719281273 = messageFormatterFn((function(  ) {
  return function (d) { return "Connect"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2025330659 = messageFormatterFn((function(  ) {
  return function (d) { return "file"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1753726805 = messageFormatterFn((function(  ) {
  return function (d) { return "folder"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2126432261 = messageFormatterFn((function(  ) {
  return function (d) { return "Kind"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b290255707 = messageFormatterFn((function(  ) {
  return function (d) { return "Last Modified On"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2047961806 = messageFormatterFn((function(  ) {
  return function (d) { return "Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1840312086 = messageFormatterFn((function(  ) {
  return function (d) { return "No files or folders matching the searched name were found"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1946705393 = messageFormatterFn((function(  ) {
  return function (d) { return "Search"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1267830936 = messageFormatterFn((function(  ) {
  return function (d) { return "Search not supported for Business accounts"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a347448864 = messageFormatterFn((function(  ) {
  return function (d) { return "Search Results"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1607928550 = messageFormatterFn((function(  ) {
  return function (d) { return "signed in as " + d.user + " "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b939486176 = messageFormatterFn((function(  ) {
  return function (d) { return "sign out"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1023705213 = messageFormatterFn((function(  ) {
  return function (d) { return "The URL you entered is invalid or points to a file you don't have permission to view"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1053674704 = messageFormatterFn((function(  ) {
  return function (d) { return "Add a comment."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b849113558 = messageFormatterFn((function(  ) {
  return function (d) { return "Add a comment. @mention to notify someone."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a586234441 = messageFormatterFn((function(  ) {
  return function (d) { return "Add a snapshot of the view to your comment"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b417380523 = messageFormatterFn((function(  ) {
  return function (d) { return "Couldn't create a snapshot of the view"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1465273848 = messageFormatterFn((function(  ) {
  return function (d) { return "Applying the snapshot's filters and selection to the view..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1885602008 = messageFormatterFn((function(  ) {
  return function (d) { return "Couldn't apply snapshot from " + d.user + " to the view"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a937118726 = messageFormatterFn((function(  ) {
  return function (d) { return "Something went wrong"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a544430526 = messageFormatterFn((function(  ) {
  return function (d) { return "Close panel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a169003142 = messageFormatterFn((function(  ) {
  return function (d) { return "Comments"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a253711618 = messageFormatterFn((function(  ) {
  return function (d) { return "You no longer have add comment permission."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b127737520 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return plural(d.itemCount, 0, pluralFuncs.en, { one: function() { return "User";}, other: function() { return d.formattedItemCount + " users";} }) + " will not be notified about " + d.comment; }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.a1471531500 = messageFormatterFn((function(  ) {
  return function (d) { return "You no longer have permission to view the comments."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1524561682 = messageFormatterFn((function(  ) {
  return function (d) { return "Check your internet connection and retry."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b904005292 = messageFormatterFn((function(  ) {
  return function (d) { return "Check your internet connection and refresh to try again"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2069839777 = messageFormatterFn((function(  ) {
  return function (d) { return "Contact your administrator."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a18627952 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b103099487 = messageFormatterFn((function(  ) {
  return function (d) { return "Delete"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1995720738 = messageFormatterFn((function(  ) {
  return function (d) { return "This message has already been deleted."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1713758616 = messageFormatterFn((function(  ) {
  return function (d) { return "You do not have permission to delete this comment."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1423669119 = messageFormatterFn((function(  ) {
  return function (d) { return "Delete"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a490842535 = messageFormatterFn((function(  ) {
  return function (d) { return "Failed to download image"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1117524006 = messageFormatterFn((function(  ) {
  return function (d) { return "An unknown error has occurred"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1513402832 = messageFormatterFn((function(  ) {
  return function (d) { return "Failed to get comments"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a333220967 = messageFormatterFn((function(  ) {
  return function (d) { return "Failed to get image"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1591409219 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1104549106 = messageFormatterFn((function(  ) {
  return function (d) { return "Unable to load comments"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2089505580 = messageFormatterFn((function(  ) {
  return function (d) { return "Loading comments..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1250654285 = messageFormatterFn((function(  ) {
  return function (d) { return "Message is too long"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1015530127 = messageFormatterFn((function(  ) {
  return function (d) { return "No comments on this view."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b229925326 = messageFormatterFn((function(  ) {
  return function (d) { return "@mention someone in your comment to notify them"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1889096782 = messageFormatterFn((function(  ) {
  return function (d) { return "Post"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b163283605 = messageFormatterFn((function(  ) {
  return function (d) { return "Remove snapshot"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1237763732 = messageFormatterFn((function(  ) {
  return function (d) { return "Retry"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1392247716 = messageFormatterFn((function(  ) {
  return function (d) { return "Couldn't send."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1523397989 = messageFormatterFn((function(  ) {
  return function (d) { return "Tap to retry"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b274322310 = messageFormatterFn((function(  ) {
  return function (d) { return "Unable to load comments"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1861665231 = messageFormatterFn((function(  ) {
  return function (d) { return d.user + " doesn't have permissions to see this view"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a221714838 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return plural(d.itemCount, 0, pluralFuncs.en, { one: function() { return d.formattedItemCount + " user";}, other: function() { return d.formattedItemCount + " users";} }) + " won't be notified"; }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.b1318343138 = messageFormatterFn((function(  ) {
  return function (d) { return d.user + " lacks an email address in their Tableau account"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b481362245 = messageFormatterFn((function(  ) {
  return function (d) { return d.user + " doesn’t have permissions to see comments"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1797312956 = messageFormatterFn((function(  ) {
  return function (d) { return "User will not be notified"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a631426777 = messageFormatterFn((function(  ) {
  return function (d) { return "User Removed"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2079754917 = messageFormatterFn((function(  ) {
  return function (d) { return "View"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1682182902 = messageFormatterFn((function(  ) {
  return function (d) { return "Remember Password"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b33920924 = messageFormatterFn((function(  ) {
  return function (d) { return "Authentication:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a125071357 = messageFormatterFn((function(  ) {
  return function (d) { return "Microsoft Azure HDInsight Service"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1323979673 = messageFormatterFn((function(  ) {
  return function (d) { return "Integrated Authentication"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2061365663 = messageFormatterFn((function(  ) {
  return function (d) { return "Kerberos"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b303434483 = messageFormatterFn((function(  ) {
  return function (d) { return "LDAP"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b205104002 = messageFormatterFn((function(  ) {
  return function (d) { return "No Authentication"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1757495000 = messageFormatterFn((function(  ) {
  return function (d) { return "SAML IdP"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b466720944 = messageFormatterFn((function(  ) {
  return function (d) { return "Teradata Database"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a311133740 = messageFormatterFn((function(  ) {
  return function (d) { return "Username and Password"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b813803351 = messageFormatterFn((function(  ) {
  return function (d) { return "Active Directory Password"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1109256476 = messageFormatterFn((function(  ) {
  return function (d) { return "Username"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a218675035 = messageFormatterFn((function(  ) {
  return function (d) { return "Windows Authentication"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2080762645 = messageFormatterFn((function(  ) {
  return function (d) { return "Direct"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1366923348 = messageFormatterFn((function(  ) {
  return function (d) { return "HiveServer2"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1399224630 = messageFormatterFn((function(  ) {
  return function (d) { return "Impala"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a489929650 = messageFormatterFn((function(  ) {
  return function (d) { return "SharkServer (Shark 0.8.1 and earlier)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1992036394 = messageFormatterFn((function(  ) {
  return function (d) { return "SharkServer2 (Shark 0.9.*)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1522591402 = messageFormatterFn((function(  ) {
  return function (d) { return "SparkThriftServer (Spark 1.1 and later)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1091946038 = messageFormatterFn((function(  ) {
  return function (d) { return "ZooKeeper"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2034559786 = messageFormatterFn((function(  ) {
  return function (d) { return "SingleNode"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a26827269 = messageFormatterFn((function(  ) {
  return function (d) { return "MultiNode"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a626249337 = messageFormatterFn((function(  ) {
  return function (d) { return "Add SQL statements to be executed at connect time"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a9829008 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a339708011 = messageFormatterFn((function(  ) {
  return function (d) { return "Initial SQL"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b956419018 = messageFormatterFn((function(  ) {
  return function (d) { return "Insert"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1320678518 = messageFormatterFn((function(  ) {
  return function (d) { return "Show Initial SQL"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1707293669 = messageFormatterFn((function(  ) {
  return function (d) { return "Hide Initial SQL"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a634131777 = messageFormatterFn((function(  ) {
  return function (d) { return "Binary"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1510905128 = messageFormatterFn((function(  ) {
  return function (d) { return "HTTP"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1708409848 = messageFormatterFn((function(  ) {
  return function (d) { return "No Transport Type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1808245255 = messageFormatterFn((function(  ) {
  return function (d) { return "SASL"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a824791310 = messageFormatterFn((function(  ) {
  return function (d) { return "Copy"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1358687201 = messageFormatterFn((function(  ) {
  return function (d) { return "Cut"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1946751056 = messageFormatterFn((function(  ) {
  return function (d) { return "Paste"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b637441164 = messageFormatterFn((function(  ) {
  return function (d) { return "Read uncommitted data"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1930901595 = messageFormatterFn((function(  ) {
  return function (d) { return "Require Encryption"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b925271808 = messageFormatterFn((function(  ) {
  return function (d) { return "Require SSL (recommended)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1181860937 = messageFormatterFn((function(  ) {
  return function (d) { return "Keep your data safe by encrypting the data connection"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b87476619 = messageFormatterFn((function(  ) {
  return function (d) { return "Detailed Error Message"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b935903431 = messageFormatterFn((function(  ) {
  return function (d) { return "Optional"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1201480561 = messageFormatterFn((function(  ) {
  return function (d) { return "Sign In"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b544606338 = messageFormatterFn((function(  ) {
  return function (d) { return "Signing In…"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b384954460 = messageFormatterFn((function(  ) {
  return function (d) { return "Type:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b956035642 = messageFormatterFn((function(  ) {
  return function (d) { return "Username:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1283605601 = messageFormatterFn((function(  ) {
  return function (d) { return "Password:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2053829712 = messageFormatterFn((function(  ) {
  return function (d) { return "SAML IdP(Okta):"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1079906130 = messageFormatterFn((function(  ) {
  return function (d) { return d.prompt + ":"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b709024273 = messageFormatterFn((function(  ) {
  return function (d) { return "HTTP:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b284692636 = messageFormatterFn((function(  ) {
  return function (d) { return "Realm:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1306109378 = messageFormatterFn((function(  ) {
  return function (d) { return "Service Name:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1564067161 = messageFormatterFn((function(  ) {
  return function (d) { return "Host FQDN:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a247014005 = messageFormatterFn((function(  ) {
  return function (d) { return "Transport:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2117222343 = messageFormatterFn((function(  ) {
  return function (d) { return "Connect"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b968910689 = messageFormatterFn((function(  ) {
  return function (d) { return "To a File"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1294093658 = messageFormatterFn((function(  ) {
  return function (d) { return "To a Server"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a629610943 = messageFormatterFn((function(  ) {
  return function (d) { return "Hide connection details"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1558801372 = messageFormatterFn((function(  ) {
  return function (d) { return "Show connection details"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a897082197 = messageFormatterFn((function(  ) {
  return function (d) { return "Filename:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1707716302 = messageFormatterFn((function(  ) {
  return function (d) { return "Database password:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b173858064 = messageFormatterFn((function(  ) {
  return function (d) { return "Workgroup security"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b355575117 = messageFormatterFn((function(  ) {
  return function (d) { return "Workgroup file:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1783673374 = messageFormatterFn((function(  ) {
  return function (d) { return "Username:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a455967869 = messageFormatterFn((function(  ) {
  return function (d) { return "Password:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1052854429 = messageFormatterFn((function(  ) {
  return function (d) { return "Browse"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1422042490 = messageFormatterFn((function(  ) {
  return function (d) { return "Browse…"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1551324537 = messageFormatterFn((function(  ) {
  return function (d) { return "Open"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1219655132 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit Custom SQL"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1095711959 = messageFormatterFn((function(  ) {
  return function (d) { return "Convert to SQL"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a368823831 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b690235051 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1088246857 = messageFormatterFn((function(  ) {
  return function (d) { return "Enter SQL query here. For example, 'SELECT * FROM table_name'"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1297433604 = messageFormatterFn((function(  ) {
  return function (d) { return "Insert Parameter:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1668497494 = messageFormatterFn((function(  ) {
  return function (d) { return "Create a New Parameter..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1144743934 = messageFormatterFn((function(  ) {
  return function (d) { return "Preview Results..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1449181573 = messageFormatterFn((function(  ) {
  return function (d) { return "Add Action"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a126964085 = messageFormatterFn((function(  ) {
  return function (d) { return "Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1901411760 = messageFormatterFn((function(  ) {
  return function (d) { return "Run On"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2068327239 = messageFormatterFn((function(  ) {
  return function (d) { return "Fields"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a677843237 = messageFormatterFn((function(  ) {
  return function (d) { return "Source"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b772106921 = messageFormatterFn((function(  ) {
  return function (d) { return "Select"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1040521257 = messageFormatterFn((function(  ) {
  return function (d) { return "Hover"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1146806022 = messageFormatterFn((function(  ) {
  return function (d) { return "Menu"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a882157157 = messageFormatterFn((function(  ) {
  return function (d) { return "Above"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1842802659 = messageFormatterFn((function(  ) {
  return function (d) { return "Above or equal to"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b266175882 = messageFormatterFn((function(  ) {
  return function (d) { return "Actions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1988497984 = messageFormatterFn((function(  ) {
  return function (d) { return "Add Me"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b957523831 = messageFormatterFn((function(  ) {
  return function (d) { return "Alert Invalid"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a799666605 = messageFormatterFn((function(  ) {
  return function (d) { return "Alert Suspended"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b900482457 = messageFormatterFn((function(  ) {
  return function (d) { return "This alert is visible only to recipients."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1170834069 = messageFormatterFn((function(  ) {
  return function (d) { return "This alert is visible to everyone."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a272368871 = messageFormatterFn((function(  ) {
  return function (d) { return "Back"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1852586489 = messageFormatterFn((function(  ) {
  return function (d) { return "Below"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b526630135 = messageFormatterFn((function(  ) {
  return function (d) { return "Below or equal to"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a85533770 = messageFormatterFn((function(  ) {
  return function (d) { return "Change owner"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1987145295 = messageFormatterFn((function(  ) {
  return function (d) { return "Change owner"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1851666224 = messageFormatterFn((function(  ) {
  return function (d) { return "Choose an owner for the alert \"" + d.alertSubject + "\""; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1998425724 = messageFormatterFn((function(  ) {
  return function (d) { return "Close"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a33435572 = messageFormatterFn((function(  ) {
  return function (d) { return "True"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1714687687 = messageFormatterFn((function(  ) {
  return function (d) { return "False"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1330692492 = messageFormatterFn((function(  ) {
  return function (d) { return "Failed"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1266007411 = messageFormatterFn((function(  ) {
  return function (d) { return "—"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1924727078 = messageFormatterFn((function(  ) {
  return function (d) { return "Custom (" + d.viewName + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b605524899 = messageFormatterFn((function(  ) {
  return function (d) { return "Delete"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a997798026 = messageFormatterFn((function(  ) {
  return function (d) { return "Details"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1499363825 = messageFormatterFn((function(  ) {
  return function (d) { return "Activity"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b976535522 = messageFormatterFn((function(  ) {
  return function (d) { return "Condition"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1937685151 = messageFormatterFn((function(  ) {
  return function (d) { return "Current status"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b745794774 = messageFormatterFn((function(  ) {
  return function (d) { return "Email sent"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1186704078 = messageFormatterFn((function(  ) {
  return function (d) { return "Frequency"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b189848569 = messageFormatterFn((function(  ) {
  return function (d) { return "Last checked"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a291891063 = messageFormatterFn((function(  ) {
  return function (d) { return "Last triggered"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b469411980 = messageFormatterFn((function(  ) {
  return function (d) { return "Measure"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b497849749 = messageFormatterFn((function(  ) {
  return function (d) { return "Notification"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a751348324 = messageFormatterFn((function(  ) {
  return function (d) { return "Operator"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1372311991 = messageFormatterFn((function(  ) {
  return function (d) { return "Owner"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1857550458 = messageFormatterFn((function(  ) {
  return function (d) { return "Recipients"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1757991807 = messageFormatterFn((function(  ) {
  return function (d) { return "Threshold"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b134141275 = messageFormatterFn((function(  ) {
  return function (d) { return "View"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1279823364 = messageFormatterFn((function(  ) {
  return function (d) { return "Alert Overview"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a800557884 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b481213481 = messageFormatterFn((function(  ) {
  return function (d) { return "Equal to"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b938507955 = messageFormatterFn((function(  ) {
  return function (d) { return "Custom (autosaved)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1593938012 = messageFormatterFn((function(  ) {
  return function (d) { return "Daily at most"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1819372658 = messageFormatterFn((function(  ) {
  return function (d) { return "As frequently as possible"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a437680036 = messageFormatterFn((function(  ) {
  return function (d) { return "Hourly at most"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1209439668 = messageFormatterFn((function(  ) {
  return function (d) { return "Once, the first time it's true"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b985608301 = messageFormatterFn((function(  ) {
  return function (d) { return d.interval + " minutes"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a60398004 = messageFormatterFn((function(  ) {
  return function (d) { return "Weekly at most"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b286260071 = messageFormatterFn((function(  ) {
  return function (d) { return "Invalid on "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1547226892 = messageFormatterFn((function(  ) {
  return function (d) { return "Invalid"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a315223849 = messageFormatterFn((function(  ) {
  return function (d) { return "Last triggered " + d.lastTriggeredTime; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1358107998 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1898984149 = messageFormatterFn((function(  ) {
  return function (d) { return "Alerts"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1796187200 = messageFormatterFn((function(  ) {
  return function (d) { return "Retry"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b668102034 = messageFormatterFn((function(  ) {
  return function (d) { return "Check your internet connection and retry"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a874320269 = messageFormatterFn((function(  ) {
  return function (d) { return "Unable to load alerts"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1093110127 = messageFormatterFn((function(  ) {
  return function (d) { return "Loading alerts..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1533386505 = messageFormatterFn((function(  ) {
  return function (d) { return "Never"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1536579079 = messageFormatterFn((function(  ) {
  return function (d) { return "Never triggered"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1815470685 = messageFormatterFn((function(  ) {
  return function (d) { return "alert bell symbol"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1877719681 = messageFormatterFn((function(  ) {
  return function (d) { return "Create"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1742953853 = messageFormatterFn((function(  ) {
  return function (d) { return "Create an alert and we'll email you when your data meets those conditions."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1153162538 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1134737951 = messageFormatterFn((function(  ) {
  return function (d) { return "Select a numeric axis of a chart. Then click Create."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2012711288 = messageFormatterFn((function(  ) {
  return function (d) { return "No alerts on this view"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a836390241 = messageFormatterFn((function(  ) {
  return function (d) { return d.recipientCount + " recipients"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1237097652 = messageFormatterFn((function(  ) {
  return function (d) { return d.recipientCount + " recipient"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1086072710 = messageFormatterFn((function(  ) {
  return function (d) { return "Original"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1025518958 = messageFormatterFn((function(  ) {
  return function (d) { return "Remove me"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b966778017 = messageFormatterFn((function(  ) {
  return function (d) { return "Resume"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2119178368 = messageFormatterFn((function(  ) {
  return function (d) { return "Search"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1332896963 = messageFormatterFn((function(  ) {
  return function (d) { return "Suspended on "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1360711504 = messageFormatterFn((function(  ) {
  return function (d) { return "Suspended"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1622065521 = messageFormatterFn((function(  ) {
  return function (d) { return "About"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a515915422 = messageFormatterFn((function(  ) {
  return function (d) { return "Author"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b486903922 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1229704613 = messageFormatterFn((function(  ) {
  return function (d) { return "Catalog"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a429400399 = messageFormatterFn((function(  ) {
  return function (d) { return "Clear"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a437498370 = messageFormatterFn((function(  ) {
  return function (d) { return "Close"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b536770273 = messageFormatterFn((function(  ) {
  return function (d) { return "Columns"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1188821536 = messageFormatterFn((function(  ) {
  return function (d) { return "Columns (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a58568674 = messageFormatterFn((function(  ) {
  return function (d) { return "Couldn't find the table. Do you have the right URL?"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a486185787 = messageFormatterFn((function(  ) {
  return function (d) { return "Database: " + d.databaseName; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1195079450 = messageFormatterFn((function(  ) {
  return function (d) { return "Databases"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a821485289 = messageFormatterFn((function(  ) {
  return function (d) { return "Database Type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b662227038 = messageFormatterFn((function(  ) {
  return function (d) { return "Author: " + d.name; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2026176571 = messageFormatterFn((function(  ) {
  return function (d) { return "By " + d.displayName + " on " + d.updatedAt; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1787768284 = messageFormatterFn((function(  ) {
  return function (d) { return "Deprecated"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2002744104 = messageFormatterFn((function(  ) {
  return function (d) { return "Maintenance in progress"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a847782750 = messageFormatterFn((function(  ) {
  return function (d) { return "Stale data"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b747184095 = messageFormatterFn((function(  ) {
  return function (d) { return "Warning"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1721240371 = messageFormatterFn((function(  ) {
  return function (d) { return "Data Source Place Page"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1817097808 = messageFormatterFn((function(  ) {
  return function (d) { return "Data Sources"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1583882191 = messageFormatterFn((function(  ) {
  return function (d) { return "Data Sources (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1763055845 = messageFormatterFn((function(  ) {
  return function (d) { return "Modified"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b696545794 = messageFormatterFn((function(  ) {
  return function (d) { return "Description"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b584969837 = messageFormatterFn((function(  ) {
  return function (d) { return "Details Usage"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a781790702 = messageFormatterFn((function(  ) {
  return function (d) { return "Downstream Data Sources"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2017942001 = messageFormatterFn((function(  ) {
  return function (d) { return "Downstream Data Sources (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a381920010 = messageFormatterFn((function(  ) {
  return function (d) { return "Downstream Sheets"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1746461781 = messageFormatterFn((function(  ) {
  return function (d) { return "Downstream Sheets (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b395255327 = messageFormatterFn((function(  ) {
  return function (d) { return "Downstream Usage"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b391220088 = messageFormatterFn((function(  ) {
  return function (d) { return "Users"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1324277911 = messageFormatterFn((function(  ) {
  return function (d) { return "Users (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1443967481 = messageFormatterFn((function(  ) {
  return function (d) { return "Downstream Workbooks"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b591678906 = messageFormatterFn((function(  ) {
  return function (d) { return "Downstream Workbooks (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1915286576 = messageFormatterFn((function(  ) {
  return function (d) { return "Send an email"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b568937008 = messageFormatterFn((function(  ) {
  return function (d) { return "Less"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b531115892 = messageFormatterFn((function(  ) {
  return function (d) { return "More"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1906361782 = messageFormatterFn((function(  ) {
  return function (d) { return "Error"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1292719091 = messageFormatterFn((function(  ) {
  return function (d) { return "Fields"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2103423310 = messageFormatterFn((function(  ) {
  return function (d) { return "Fields (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1282358535 = messageFormatterFn((function(  ) {
  return function (d) { return "Files"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1092044203 = messageFormatterFn((function(  ) {
  return function (d) { return "Filtered"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b262435107 = messageFormatterFn((function(  ) {
  return function (d) { return "Data Sources"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1178775596 = messageFormatterFn((function(  ) {
  return function (d) { return "Columns"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b807444820 = messageFormatterFn((function(  ) {
  return function (d) { return "Connected Data Sources"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1712920660 = messageFormatterFn((function(  ) {
  return function (d) { return "Connected Sheets"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a728093728 = messageFormatterFn((function(  ) {
  return function (d) { return "#" + " of Connections"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2113141729 = messageFormatterFn((function(  ) {
  return function (d) { return "Connection Type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1518888587 = messageFormatterFn((function(  ) {
  return function (d) { return "Description"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2052396622 = messageFormatterFn((function(  ) {
  return function (d) { return "Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2141703536 = messageFormatterFn((function(  ) {
  return function (d) { return "Owned Data Sources"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a48598779 = messageFormatterFn((function(  ) {
  return function (d) { return "Owned Workbooks"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1976409470 = messageFormatterFn((function(  ) {
  return function (d) { return "Owner"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1139075321 = messageFormatterFn((function(  ) {
  return function (d) { return "Owners"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1785476828 = messageFormatterFn((function(  ) {
  return function (d) { return "Popularity"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1423137430 = messageFormatterFn((function(  ) {
  return function (d) { return "Server"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a851942619 = messageFormatterFn((function(  ) {
  return function (d) { return "Sheets"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1012300152 = messageFormatterFn((function(  ) {
  return function (d) { return "#" + " of Tables"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a597324812 = messageFormatterFn((function(  ) {
  return function (d) { return "Tables"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1880787008 = messageFormatterFn((function(  ) {
  return function (d) { return "Tags"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1858367839 = messageFormatterFn((function(  ) {
  return function (d) { return "Type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b480187679 = messageFormatterFn((function(  ) {
  return function (d) { return "Workbook"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1998802745 = messageFormatterFn((function(  ) {
  return function (d) { return "Hostname"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1748043687 = messageFormatterFn((function(  ) {
  return function (d) { return "Lineage"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1286998338 = messageFormatterFn((function(  ) {
  return function (d) { return "Loading…"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1783286878 = messageFormatterFn((function(  ) {
  return function (d) { return "No description available."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1386746022 = messageFormatterFn((function(  ) {
  return function (d) { return "No tables found."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1482105803 = messageFormatterFn((function(  ) {
  return function (d) { return "Owner Information"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a41685902 = messageFormatterFn((function(  ) {
  return function (d) { return "Owner's Display Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1541324953 = messageFormatterFn((function(  ) {
  return function (d) { return "Owner's Domain"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1626635312 = messageFormatterFn((function(  ) {
  return function (d) { return "Owner's Id"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1299436468 = messageFormatterFn((function(  ) {
  return function (d) { return "Owners"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1251749141 = messageFormatterFn((function(  ) {
  return function (d) { return "Owners (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1103331123 = messageFormatterFn((function(  ) {
  return function (d) { return "Owner's Site URI"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2126247371 = messageFormatterFn((function(  ) {
  return function (d) { return "Owner's User Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b777081437 = messageFormatterFn((function(  ) {
  return function (d) { return "+ " + d.count + " more"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1587731782 = messageFormatterFn((function(  ) {
  return function (d) { return "Project Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2030704437 = messageFormatterFn((function(  ) {
  return function (d) { return "Search"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b365562020 = messageFormatterFn((function(  ) {
  return function (d) { return "Send"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1522916682 = messageFormatterFn((function(  ) {
  return function (d) { return "Send Email"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1792475275 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return "To: " + plural(d.USER_COUNT, 0, pluralFuncs.en, { one: function() { return d.USER_COUNT_LOC + " recipient";}, other: function() { return d.USER_COUNT_LOC + " recipients";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.b1633629183 = messageFormatterFn((function(  ) {
  return function (d) { return "Fields in Use (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1004512888 = messageFormatterFn((function(  ) {
  return function (d) { return "Sheets"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1959697303 = messageFormatterFn((function(  ) {
  return function (d) { return "Sheets (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1506634938 = messageFormatterFn((function(  ) {
  return function (d) { return "Site Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1867919022 = messageFormatterFn((function(  ) {
  return function (d) { return "Subject"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1980282224 = messageFormatterFn((function(  ) {
  return function (d) { return "Table"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1259130695 = messageFormatterFn((function(  ) {
  return function (d) { return "Tables"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1426948927 = messageFormatterFn((function(  ) {
  return function (d) { return "Upstream Databases"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a35614656 = messageFormatterFn((function(  ) {
  return function (d) { return "Upstream Databases (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b985633515 = messageFormatterFn((function(  ) {
  return function (d) { return "Upsteam Data Sources"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a365960884 = messageFormatterFn((function(  ) {
  return function (d) { return "Upstream Tables"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a413919211 = messageFormatterFn((function(  ) {
  return function (d) { return "Upstream Tables (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b526103992 = messageFormatterFn((function(  ) {
  return function (d) { return "Upstream Usage"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a386149897 = messageFormatterFn((function(  ) {
  return function (d) { return "Workbook Id"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1372978501 = messageFormatterFn((function(  ) {
  return function (d) { return "Workbooks"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b348873788 = messageFormatterFn((function(  ) {
  return function (d) { return "Workbooks (" + d.count + ")"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2136654723 = messageFormatterFn((function(  ) {
  return function (d) { return "Loading"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b933979678 = messageFormatterFn((function(  ) {
  return function (d) { return "Live"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1699798881 = messageFormatterFn((function(  ) {
  return function (d) { return "Extract"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1936658290 = messageFormatterFn((function(  ) {
  return function (d) { return "Connection"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b947838063 = messageFormatterFn((function(  ) {
  return function (d) { return "Filters"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a659760402 = messageFormatterFn((function(  ) {
  return function (d) { return "Cross-database join"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2128579395 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a438503872 = messageFormatterFn((function(  ) {
  return function (d) { return "Using your database"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a674040967 = messageFormatterFn((function(  ) {
  return function (d) { return "Using Tableau"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1307573579 = messageFormatterFn((function(  ) {
  return function (d) { return "Use Tableau or your live database connection to perform the cross-database join. If the live database connection is used, data from the file connection may be temporarily moved to that database."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1845398108 = messageFormatterFn((function(  ) {
  return function (d) { return "Use Tableau to perform the cross-database join"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a411004451 = messageFormatterFn((function(  ) {
  return function (d) { return "Comma"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b368659549 = messageFormatterFn((function(  ) {
  return function (d) { return "Tab"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b483997825 = messageFormatterFn((function(  ) {
  return function (d) { return "Semicolon"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1743414292 = messageFormatterFn((function(  ) {
  return function (d) { return "Space"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a896903115 = messageFormatterFn((function(  ) {
  return function (d) { return "Vertical Bar"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1685547106 = messageFormatterFn((function(  ) {
  return function (d) { return "Other"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b235093100 = messageFormatterFn((function(  ) {
  return function (d) { return "Automatic"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a773932357 = messageFormatterFn((function(  ) {
  return function (d) { return "None"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b739467495 = messageFormatterFn((function(  ) {
  return function (d) { return "Field separator:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b516599906 = messageFormatterFn((function(  ) {
  return function (d) { return "Text qualifier:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1272973824 = messageFormatterFn((function(  ) {
  return function (d) { return "Character set:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a782488060 = messageFormatterFn((function(  ) {
  return function (d) { return "Locale:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b269370960 = messageFormatterFn((function(  ) {
  return function (d) { return "Drag table to union"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2077382616 = messageFormatterFn((function(  ) {
  return function (d) { return "Apply"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b968309828 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b137806641 = messageFormatterFn((function(  ) {
  return function (d) { return "Connection: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b593092693 = messageFormatterFn((function(  ) {
  return function (d) { return "Drag tables here"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b8866189 = messageFormatterFn((function(  ) {
  return function (d) { return "Tables in union: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a600859031 = messageFormatterFn((function(  ) {
  return function (d) { return "You can only union data from the same connection"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2082057339 = messageFormatterFn((function(  ) {
  return function (d) { return "Tableau can't find or recognize this table. Remove or replace the table"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a655081587 = messageFormatterFn((function(  ) {
  return function (d) { return "Search"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a44020938 = messageFormatterFn((function(  ) {
  return function (d) { return "Copy"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1395604282 = messageFormatterFn((function(  ) {
  return function (d) { return "Copy link address"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b251899894 = messageFormatterFn((function(  ) {
  return function (d) { return "Dismiss"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1827707147 = messageFormatterFn((function(  ) {
  return function (d) { return "Error Code: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b699475681 = messageFormatterFn((function(  ) {
  return function (d) { return "Unable to complete action"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a961972272 = messageFormatterFn((function(  ) {
  return function (d) { return "Copy Error Message"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b815372396 = messageFormatterFn((function(  ) {
  return function (d) { return "Go to Support"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b255654840 = messageFormatterFn((function(  ) {
  return function (d) { return "Yes"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1809682794 = messageFormatterFn((function(  ) {
  return function (d) { return "No"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b793588198 = messageFormatterFn((function(  ) {
  return function (d) { return "Error copied to clipboard"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a733957981 = messageFormatterFn((function(  ) {
  return function (d) { return "Automatic"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b168589764 = messageFormatterFn((function(  ) {
  return function (d) { return "Axis Editing Properties"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a116826502 = messageFormatterFn((function(  ) {
  return function (d) { return "Axis Range Options"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1596155136 = messageFormatterFn((function(  ) {
  return function (d) { return "Axis Titles"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1231669957 = messageFormatterFn((function(  ) {
  return function (d) { return "Days"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1607536880 = messageFormatterFn((function(  ) {
  return function (d) { return "Fixed"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1278768609 = messageFormatterFn((function(  ) {
  return function (d) { return "Fixed end"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a247547112 = messageFormatterFn((function(  ) {
  return function (d) { return "Fixed start"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b970394972 = messageFormatterFn((function(  ) {
  return function (d) { return "General"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a125144769 = messageFormatterFn((function(  ) {
  return function (d) { return "Hours"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1581978018 = messageFormatterFn((function(  ) {
  return function (d) { return "Include zero"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1260422356 = messageFormatterFn((function(  ) {
  return function (d) { return "Independent"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1511552441 = messageFormatterFn((function(  ) {
  return function (d) { return "Independent axis ranges for each row or column"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a370610397 = messageFormatterFn((function(  ) {
  return function (d) { return "Insert"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1420855721 = messageFormatterFn((function(  ) {
  return function (d) { return "Interval"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a517883563 = messageFormatterFn((function(  ) {
  return function (d) { return "Enter a valid number."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2101016678 = messageFormatterFn((function(  ) {
  return function (d) { return "Enter a valid date."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b849525218 = messageFormatterFn((function(  ) {
  return function (d) { return "ISO Quarters"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1418024994 = messageFormatterFn((function(  ) {
  return function (d) { return "ISO Weekdays"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1304678114 = messageFormatterFn((function(  ) {
  return function (d) { return "ISO Weeks"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a466843701 = messageFormatterFn((function(  ) {
  return function (d) { return "ISO Years"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2046264182 = messageFormatterFn((function(  ) {
  return function (d) { return "Positive"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2108222031 = messageFormatterFn((function(  ) {
  return function (d) { return "Logarithmic"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1973292878 = messageFormatterFn((function(  ) {
  return function (d) { return "Logarithm base must be greater than one."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1209983741 = messageFormatterFn((function(  ) {
  return function (d) { return "Log axis origin must be greater than zero."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1229928788 = messageFormatterFn((function(  ) {
  return function (d) { return "Major Tick Marks"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1770199800 = messageFormatterFn((function(  ) {
  return function (d) { return "Major tick interval must be greater than zero."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1616793128 = messageFormatterFn((function(  ) {
  return function (d) { return "Minor Tick Marks"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a732038404 = messageFormatterFn((function(  ) {
  return function (d) { return "Minor tick interval must be greater than zero."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a157011665 = messageFormatterFn((function(  ) {
  return function (d) { return "Minutes"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b490170985 = messageFormatterFn((function(  ) {
  return function (d) { return "Months"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b932790308 = messageFormatterFn((function(  ) {
  return function (d) { return "None"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a22527915 = messageFormatterFn((function(  ) {
  return function (d) { return "Quarters"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b403943712 = messageFormatterFn((function(  ) {
  return function (d) { return "Range"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a121722113 = messageFormatterFn((function(  ) {
  return function (d) { return "Reset"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2072550554 = messageFormatterFn((function(  ) {
  return function (d) { return "Reversed"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1761425869 = messageFormatterFn((function(  ) {
  return function (d) { return "Scale"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1829038991 = messageFormatterFn((function(  ) {
  return function (d) { return "Seconds"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a878507177 = messageFormatterFn((function(  ) {
  return function (d) { return "Show times"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1448908740 = messageFormatterFn((function(  ) {
  return function (d) { return "Subtitle"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1596485665 = messageFormatterFn((function(  ) {
  return function (d) { return "Symmetric"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2012938208 = messageFormatterFn((function(  ) {
  return function (d) { return "Synchronize dual axes"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1494018867 = messageFormatterFn((function(  ) {
  return function (d) { return "Tick interval"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a739891352 = messageFormatterFn((function(  ) {
  return function (d) { return "Tick interval (powers of)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1431600146 = messageFormatterFn((function(  ) {
  return function (d) { return "Tick Marks"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b298200556 = messageFormatterFn((function(  ) {
  return function (d) { return "Tick origin"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2012363722 = messageFormatterFn((function(  ) {
  return function (d) { return "Title"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a495382896 = messageFormatterFn((function(  ) {
  return function (d) { return "Uniform"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1525100723 = messageFormatterFn((function(  ) {
  return function (d) { return "Uniform axis range for all rows or columns"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b733444312 = messageFormatterFn((function(  ) {
  return function (d) { return "Unit"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a251521713 = messageFormatterFn((function(  ) {
  return function (d) { return "Weeks"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2023043528 = messageFormatterFn((function(  ) {
  return function (d) { return "Years"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a273976791 = messageFormatterFn((function(  ) {
  return function (d) { return "Export As Version"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1519139174 = messageFormatterFn((function(  ) {
  return function (d) { return "This action will save a new workbook and will not overwrite your existing workbook."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b189887043 = messageFormatterFn((function(  ) {
  return function (d) { return "Export"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1966591561 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a925018336 = messageFormatterFn((function(  ) {
  return function (d) { return "Export As"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b679322458 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn More"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1064003278 = messageFormatterFn((function(  ) {
  return function (d) { return "You are currently running Tableau version " + d.VERSION + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1554450613 = messageFormatterFn((function(  ) {
  return function (d) { return "The following functionality is not available in Tableau version " + d.VERSION + ":"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1456216479 = messageFormatterFn((function(  ) {
  return function (d) { return "When you export your workbook as Tableau version " + d.VERSION + ", some functionality and visual features may be lost or degraded."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1283118476 = messageFormatterFn((function(  ) {
  return function (d) { return "Workbook functionality and features will not change when exported to Tableau " + d.VERSION + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1283119437 = messageFormatterFn((function(  ) {
  return function (d) { return "The new workbook has slight underlying changes but looks the same when exported to Tableau " + d.VERSION + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1283120398 = messageFormatterFn((function(  ) {
  return function (d) { return "The new workbook has slight underlying changes but looks the same when exported to Tableau " + d.VERSION + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1283121359 = messageFormatterFn((function(  ) {
  return function (d) { return "The new workbook has some feature and functionality loss when exported to Tableau " + d.VERSION + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1283122320 = messageFormatterFn((function(  ) {
  return function (d) { return "The new workbook has major feature and functionality loss when exported to Tableau " + d.VERSION + "."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1283123281 = messageFormatterFn((function(  ) {
  return function (d) { return "Critical content and functionality loss when exported to Tableau version " + d.VERSION + ". The workbook will open but some sheets or data sources are missing."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1436896530 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b966790658 = messageFormatterFn((function(  ) {
  return function (d) { return "Download PowerPoint"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b985017775 = messageFormatterFn((function(  ) {
  return function (d) { return "About Extension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b979122863 = messageFormatterFn((function(  ) {
  return function (d) { return "Version: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a577736630 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1970412755 = messageFormatterFn((function(  ) {
  return function (d) { return "by " + d["0"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2012242316 = messageFormatterFn((function(  ) {
  return function (d) { return "Extension URL: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b884917292 = messageFormatterFn((function(  ) {
  return function (d) { return "Instance ID: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1427276885 = messageFormatterFn((function(  ) {
  return function (d) { return "Support: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b998334643 = messageFormatterFn((function(  ) {
  return function (d) { return "View in Gallery"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2056305683 = messageFormatterFn((function(  ) {
  return function (d) { return "Developer Website"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1947550741 = messageFormatterFn((function(  ) {
  return function (d) { return "Allow Extensions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1784823148 = messageFormatterFn((function(  ) {
  return function (d) { return "This dashboard contains the following extensions, which are web applications that expand the capabilities of Tableau. To allow these extensions to run in the dashboard, click OK. "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a86263706 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more about how extensions access your data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a784999736 = messageFormatterFn((function(  ) {
  return function (d) { return "Extension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1069438952 = messageFormatterFn((function(  ) {
  return function (d) { return "Created By"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1358976106 = messageFormatterFn((function(  ) {
  return function (d) { return "Full Data Access"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2051943848 = messageFormatterFn((function(  ) {
  return function (d) { return "URL"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1757104658 = messageFormatterFn((function(  ) {
  return function (d) { return "Allow Extension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1166870441 = messageFormatterFn((function(  ) {
  return function (d) { return "Allow "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1569575361 = messageFormatterFn((function(  ) {
  return function (d) { return "This dashboard contains the following extension, which is a web application that expands the capabilities of Tableau. To allow this extension to run in the dashboard, click OK."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a26978240 = messageFormatterFn((function(  ) {
  return function (d) { return "Created by:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b393760315 = messageFormatterFn((function(  ) {
  return function (d) { return "Extension URL:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a462320651 = messageFormatterFn((function(  ) {
  return function (d) { return "Extension Name:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1617238258 = messageFormatterFn((function(  ) {
  return function (d) { return "Full Data Access:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b141622681 = messageFormatterFn((function(  ) {
  return function (d) { return "Yes"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b250538867 = messageFormatterFn((function(  ) {
  return function (d) { return "No"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1442095093 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2106885620 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b702999964 = messageFormatterFn((function(  ) {
  return function (d) { return "Go to Sheet"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1408619231 = messageFormatterFn((function(  ) {
  return function (d) { return "Go to Sheet"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1000244920 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1723790555 = messageFormatterFn((function(  ) {
  return function (d) { return "Enter sheet name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2069928378 = messageFormatterFn((function(  ) {
  return function (d) { return "Choose sheet from list"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b479743807 = messageFormatterFn((function(  ) {
  return function (d) { return "Type or select sheet to go to"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a364363623 = messageFormatterFn((function(  ) {
  return function (d) { return "that localize/widgets now requires to exist"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a349254702 = messageFormatterFn((function(  ) {
  return function (d) { return "do not localize"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1193270721 = messageFormatterFn((function(  ) {
  return function (d) { return "Center Image"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a308514941 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit Image Object"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1804510315 = messageFormatterFn((function(  ) {
  return function (d) { return "Fit Image"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1462883740 = messageFormatterFn((function(  ) {
  return function (d) { return "Choose an image..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b129089618 = messageFormatterFn((function(  ) {
  return function (d) { return "Choose"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b424171433 = messageFormatterFn((function(  ) {
  return function (d) { return "Image"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b521992972 = messageFormatterFn((function(  ) {
  return function (d) { return "Options"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b825731590 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a365438392 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b500365626 = messageFormatterFn((function(  ) {
  return function (d) { return "Apply"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a844604035 = messageFormatterFn((function(  ) {
  return function (d) { return "Target URL"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1034048028 = messageFormatterFn((function(  ) {
  return function (d) { return "Alt Text"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a221471585 = messageFormatterFn((function(  ) {
  return function (d) { return "Initial SQL"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1954425344 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1939735710 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b844015617 = messageFormatterFn((function(  ) {
  return function (d) { return "Enter SQL query here. For example, 'CREATE TABLE " + "#" + "TempTable(x varchar(25));'"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a230538473 = messageFormatterFn((function(  ) {
  return function (d) { return "SQL statements to be executed at connect time:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b206540180 = messageFormatterFn((function(  ) {
  return function (d) { return "Insert:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2008613952 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn More"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b762556483 = messageFormatterFn((function(  ) {
  return function (d) { return "Give your Metric a name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1298498858 = messageFormatterFn((function(  ) {
  return function (d) { return "Metric Title"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2076100336 = messageFormatterFn((function(  ) {
  return function (d) { return "No Field Selected"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1076269091 = messageFormatterFn((function(  ) {
  return function (d) { return "Successfully created metric: " + d.metricName; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b23501188 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: Failed to create metric"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b184623111 = messageFormatterFn((function(  ) {
  return function (d) { return "_New Metric"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1259011671 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: Can't save Metric with no selected field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1061946458 = messageFormatterFn((function(  ) {
  return function (d) { return "Cross-Database Join"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b687874403 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: Unknown Action Type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2051952890 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: Tableau Server could not find that Data Source"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1574804099 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: Fetch request failed. This is probably due to a missing API key, or CORS misconfiguration"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1533389822 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: Failed to fetch information for that datasource"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2027741962 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: API Key Cookie Not Found"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1011105636 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: Failed to fetch field list"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a882033088 = messageFormatterFn((function(  ) {
  return function (d) { return "Placeholder for Reference Link"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b860219744 = messageFormatterFn((function(  ) {
  return function (d) { return "PERIOD"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1620735268 = messageFormatterFn((function(  ) {
  return function (d) { return "HOUR"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1295098034 = messageFormatterFn((function(  ) {
  return function (d) { return "DAY"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2040453940 = messageFormatterFn((function(  ) {
  return function (d) { return "WEEK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1160602666 = messageFormatterFn((function(  ) {
  return function (d) { return "MONTH"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2097599805 = messageFormatterFn((function(  ) {
  return function (d) { return "YEAR"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b828586484 = messageFormatterFn((function(  ) {
  return function (d) { return "Transport Error: Please try again in a moment"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1536650015 = messageFormatterFn((function(  ) {
  return function (d) { return "Updated " + d.lastUpdated; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1888031461 = messageFormatterFn((function(  ) {
  return function (d) { return "PAST"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2091690144 = messageFormatterFn((function(  ) {
  return function (d) { return "AQL Query Failed"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b677299900 = messageFormatterFn((function(  ) {
  return function (d) { return "Unable to make HTTPS request for metric value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b484411812 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: Unable to query type of column " + d.columnName; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1970167468 = messageFormatterFn((function(  ) {
  return function (d) { return "No Value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a426544938 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: No metric value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1394709664 = messageFormatterFn((function(  ) {
  return function (d) { return "loading ..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2052514566 = messageFormatterFn((function(  ) {
  return function (d) { return "Aggregation: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1285205762 = messageFormatterFn((function(  ) {
  return function (d) { return "Measure: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b423336516 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2027668013 = messageFormatterFn((function(  ) {
  return function (d) { return ","; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1996121455 = messageFormatterFn((function(  ) {
  return function (d) { return ", "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1365461479 = messageFormatterFn((function(  ) {
  return function (d) { return "Collapse"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a41215258 = messageFormatterFn((function(  ) {
  return function (d) { return "Expand"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1862988796 = messageFormatterFn((function(  ) {
  return function (d) { return "Boolean"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1052631169 = messageFormatterFn((function(  ) {
  return function (d) { return "Date-time"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1269385486 = messageFormatterFn((function(  ) {
  return function (d) { return "Date"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1125961170 = messageFormatterFn((function(  ) {
  return function (d) { return "Number (Whole)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a392483102 = messageFormatterFn((function(  ) {
  return function (d) { return "Number"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1140560984 = messageFormatterFn((function(  ) {
  return function (d) { return "Spatial Data"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2113374539 = messageFormatterFn((function(  ) {
  return function (d) { return "String"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a926655243 = messageFormatterFn((function(  ) {
  return function (d) { return "Dimensions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2013147201 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit synonyms"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a651973592 = messageFormatterFn((function(  ) {
  return function (d) { return "Add other terms to refer to the field \"" + d.fieldLabel + "\". Use commas to separate each term."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1697870004 = messageFormatterFn((function(  ) {
  return function (d) { return "Synonyms"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a962653882 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit synonyms: " + d.fieldLabel; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b879210913 = messageFormatterFn((function(  ) {
  return function (d) { return "Remote Column"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1273299662 = messageFormatterFn((function(  ) {
  return function (d) { return "Role"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1759342009 = messageFormatterFn((function(  ) {
  return function (d) { return "Type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b519006871 = messageFormatterFn((function(  ) {
  return function (d) { return "Bin Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a287877302 = messageFormatterFn((function(  ) {
  return function (d) { return "Calculated Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b897090226 = messageFormatterFn((function(  ) {
  return function (d) { return "Column Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1690816253 = messageFormatterFn((function(  ) {
  return function (d) { return "Combined Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a687823871 = messageFormatterFn((function(  ) {
  return function (d) { return "Combined Set Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2117421153 = messageFormatterFn((function(  ) {
  return function (d) { return "Group Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a647212673 = messageFormatterFn((function(  ) {
  return function (d) { return "Hierarchical Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b357575676 = messageFormatterFn((function(  ) {
  return function (d) { return "Set Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a928312927 = messageFormatterFn((function(  ) {
  return function (d) { return "Field Details"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a354811418 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data will recognize field values only if you surround them with quotation marks. Republish the data source to better analyze it."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1016506861 = messageFormatterFn((function(  ) {
  return function (d) { return "Lost connection to the data source during analysis."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1836371777 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data will recognize field values only if you surround them with quotation marks."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1087277240 = messageFormatterFn((function(  ) {
  return function (d) { return "Field analysis disabled due to user filters."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b311029599 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data will recognize values only if you surround them with quotation marks."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1682347878 = messageFormatterFn((function(  ) {
  return function (d) { return "Failed to index field."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2084008367 = messageFormatterFn((function(  ) {
  return function (d) { return "This field won't be available in Ask Data"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a712690088 = messageFormatterFn((function(  ) {
  return function (d) { return "Can’t analyze field due to a system error."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1281751069 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask the data source owner to fix and republish. This field won’t be available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1641897948 = messageFormatterFn((function(  ) {
  return function (d) { return "Formula is invalid."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1952072053 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data doesn’t support indexing this field and won’t be able to recognize unquoted values at this time."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a971576964 = messageFormatterFn((function(  ) {
  return function (d) { return "Indexing isn't supported."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a51079122 = messageFormatterFn((function(  ) {
  return function (d) { return "Field is unsupported by Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b513090757 = messageFormatterFn((function(  ) {
  return function (d) { return "Fields of type Latitude or Longitude aren’t available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1060619074 = messageFormatterFn((function(  ) {
  return function (d) { return "This field’s default aggregation type is unsupported and won’t be available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a793580197 = messageFormatterFn((function(  ) {
  return function (d) { return "This field’s name contains an invalid character and won’t be available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2030009374 = messageFormatterFn((function(  ) {
  return function (d) { return "The field name can’t be a number, value, or date and won’t be available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b308339178 = messageFormatterFn((function(  ) {
  return function (d) { return "This field’s name is longer than the 50 character limit. This field won’t be available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b993050558 = messageFormatterFn((function(  ) {
  return function (d) { return "The field name is a reserved term and won’t be available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a749902776 = messageFormatterFn((function(  ) {
  return function (d) { return "Field names must be at least 1 character long. This field won’t be available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1935218087 = messageFormatterFn((function(  ) {
  return function (d) { return "Cluster fields aren't available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b537386290 = messageFormatterFn((function(  ) {
  return function (d) { return "Combined fields aren't available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1886249718 = messageFormatterFn((function(  ) {
  return function (d) { return "Combined set fields aren't available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1992110430 = messageFormatterFn((function(  ) {
  return function (d) { return "Hierarchy fields aren't available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1688113393 = messageFormatterFn((function(  ) {
  return function (d) { return "Set fields aren't available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b198478212 = messageFormatterFn((function(  ) {
  return function (d) { return "Table calculations aren’t available in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1447479875 = messageFormatterFn((function(  ) {
  return function (d) { return "Continuous dimension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a665580731 = messageFormatterFn((function(  ) {
  return function (d) { return "Continuous measure"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1088531604 = messageFormatterFn((function(  ) {
  return function (d) { return "Nominal dimension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2079700004 = messageFormatterFn((function(  ) {
  return function (d) { return "Nominal measure"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a75861377 = messageFormatterFn((function(  ) {
  return function (d) { return "Ordinal dimension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1218342777 = messageFormatterFn((function(  ) {
  return function (d) { return "Ordinal measure"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a11239898 = messageFormatterFn((function(  ) {
  return function (d) { return "Dimension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1178052114 = messageFormatterFn((function(  ) {
  return function (d) { return "Measure"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1754684930 = messageFormatterFn((function(  ) {
  return function (d) { return "Unknown"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1568142134 = messageFormatterFn((function(  ) {
  return function (d) { return "Description"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1040293756 = messageFormatterFn((function(  ) {
  return function (d) { return "Details"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a619566114 = messageFormatterFn((function(  ) {
  return function (d) { return "Domain Values"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1095843010 = messageFormatterFn((function(  ) {
  return function (d) { return "Field Info"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a548193696 = messageFormatterFn((function(  ) {
  return function (d) { return "Formula"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b429479692 = messageFormatterFn((function(  ) {
  return function (d) { return "Synonyms"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a990196815 = messageFormatterFn((function(  ) {
  return function (d) { return "Value Distribution"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1765333779 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return d.rowCount + " " + plural(d.rowCounter, 0, pluralFuncs.en, { one: function() { return "row";}, other: function() { return "rows";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.a1109258637 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return d.valueCount + " " + plural(d.valueCounter, 0, pluralFuncs.en, { one: function() { return "unique value";}, other: function() { return "unique values";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.a1465657229 = messageFormatterFn((function(  ) {
  return function (d) { return "End"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b655644378 = messageFormatterFn((function(  ) {
  return function (d) { return "Start"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2049386416 = messageFormatterFn((function(  ) {
  return function (d) { return "Average"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1344502035 = messageFormatterFn((function(  ) {
  return function (d) { return "Maximum"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b687585985 = messageFormatterFn((function(  ) {
  return function (d) { return "Minimum"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1405605002 = messageFormatterFn((function(  ) {
  return function (d) { return "Min, Max"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1562805369 = messageFormatterFn((function(  ) {
  return function (d) { return "Top 10k values are recognized in Ask Data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1923832793 = messageFormatterFn((function(  ) {
  return function (d) { return "Null"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a962561399 = messageFormatterFn((function(  ) {
  return function (d) { return "Find Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b285270079 = messageFormatterFn((function(  ) {
  return function (d) { return "A generated field that counts the number of rows."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1534761570 = messageFormatterFn((function(  ) {
  return function (d) { return "Republish it to finish analyzing all fields, or " + d.Retry + "try again." + d.Retry; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1971150847 = messageFormatterFn((function(  ) {
  return function (d) { return "Lost connection to the data source."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1908834813 = messageFormatterFn((function(  ) {
  return function (d) { return "Republish it to load fields, or " + d.Retry + "try again." + d.Retry; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1984541276 = messageFormatterFn((function(  ) {
  return function (d) { return "Unable to find the data source."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2000930608 = messageFormatterFn((function(  ) {
  return function (d) { return "Enable analysis so Ask Data can answer more questions and recognize unquoted values."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2001950641 = messageFormatterFn((function(  ) {
  return function (d) { return "Analysis has been disabled by the data source owner."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2019274323 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data will recognize field values only if you surround them with quotation marks."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b607519694 = messageFormatterFn((function(  ) {
  return function (d) { return "Can’t analyze data due to a system error."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b390443711 = messageFormatterFn((function(  ) {
  return function (d) { return "Republish with fewer fields so Ask Data can answer more questions and recognize unquoted values."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1669299872 = messageFormatterFn((function(  ) {
  return function (d) { return "Data source has too many fields to perform value analysis."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2033285784 = messageFormatterFn((function(  ) {
  return function (d) { return "Remove them from the data source to enable Ask Data to answer more questions and recognize field values."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1983802233 = messageFormatterFn((function(  ) {
  return function (d) { return "Value analysis disabled due to user filters."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a183232298 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data won't be able to recognize unquoted field values. Create an extract and republish to improve performance, or " + d.Retry + "try again." + d.Retry; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1576042185 = messageFormatterFn((function(  ) {
  return function (d) { return "Data source is too slow to analyze."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a658154965 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data can then answer more questions and recognize unquoted field values."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1784353740 = messageFormatterFn((function(  ) {
  return function (d) { return "Embed credentials to enable value analysis."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2056770807 = messageFormatterFn((function(  ) {
  return function (d) { return "Analyzing data to answer more questions..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1291612035 = messageFormatterFn((function(  ) {
  return function (d) { return "Encountered the following error and now waiting to " + d.Retry + "retry analysis" + d.Retry + ": "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1970031437 = messageFormatterFn((function(  ) {
  return function (d) { return "Refresh"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2084059058 = messageFormatterFn((function(  ) {
  return function (d) { return "Refresh data analysis"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b949490748 = messageFormatterFn((function(  ) {
  return function (d) { return "Analysis complete"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1660592606 = messageFormatterFn((function(  ) {
  return function (d) { return "Analysis"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1891319382 = messageFormatterFn((function(  ) {
  return function (d) { return "Enriched:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2092118234 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return d.fieldCountLoc + " " + plural(d.fieldCount, 0, pluralFuncs.en, { one: function() { return "field";}, other: function() { return "fields";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.b1938488831 = messageFormatterFn((function(  ) {
  return function (d) { return "Indexed:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a978422912 = messageFormatterFn((function(  ) {
  return function (d) { return "Skipped:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1693190484 = messageFormatterFn((function(  ) {
  return function (d) { return "No dimensions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1894511941 = messageFormatterFn((function(  ) {
  return function (d) { return "No measures"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a484437145 = messageFormatterFn((function(  ) {
  return function (d) { return "Save"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b430022962 = messageFormatterFn((function(  ) {
  return function (d) { return "Search"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1953873633 = messageFormatterFn((function(  ) {
  return function (d) { return "Invalid character. Synonyms must be UTF-8."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1383754140 = messageFormatterFn((function(  ) {
  return function (d) { return "Synonyms must not be numbers, booleans, or dates."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2068718337 = messageFormatterFn((function(  ) {
  return function (d) { return "Synonyms must be less than " + d.max + " characters."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2118104953 = messageFormatterFn((function(  ) {
  return function (d) { return "Synonyms can't contain reserved terms."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1935166221 = messageFormatterFn((function(  ) {
  return function (d) { return "Synonyms must be at least 1 character."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a207109455 = messageFormatterFn((function(  ) {
  return function (d) { return "None"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a546618709 = messageFormatterFn((function(  ) {
  return function (d) { return "Search"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1418119748 = messageFormatterFn((function(  ) {
  return function (d) { return "This field already has a filter. Edit or remove the existing one."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1012163125 = messageFormatterFn((function(  ) {
  return function (d) { return "Can't use this field since there are no more aggregation types available."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1382812968 = messageFormatterFn((function(  ) {
  return function (d) { return d.baseTitle + " - Ask Data"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a459324008 = messageFormatterFn((function(  ) {
  return function (d) { return "All"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1960065586 = messageFormatterFn((function(  ) {
  return function (d) { return "Contains"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1967499315 = messageFormatterFn((function(  ) {
  return function (d) { return "Ends with"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1148019047 = messageFormatterFn((function(  ) {
  return function (d) { return "Does not contain"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1155452776 = messageFormatterFn((function(  ) {
  return function (d) { return "Does not end with"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1816048783 = messageFormatterFn((function(  ) {
  return function (d) { return "Does not start with"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b928240541 = messageFormatterFn((function(  ) {
  return function (d) { return "Specific Values"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b508724890 = messageFormatterFn((function(  ) {
  return function (d) { return "Starts with"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1855130018 = messageFormatterFn((function(  ) {
  return function (d) { return "Categorical filter tabs"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a203588297 = messageFormatterFn((function(  ) {
  return function (d) { return "Wildcard"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b609418815 = messageFormatterFn((function(  ) {
  return function (d) { return "Copy"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2015144125 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit workbook"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a954979106 = messageFormatterFn((function(  ) {
  return function (d) { return "Exclude"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a39408732 = messageFormatterFn((function(  ) {
  return function (d) { return "Give Feedback"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b434899101 = messageFormatterFn((function(  ) {
  return function (d) { return "Feedback"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b349655657 = messageFormatterFn((function(  ) {
  return function (d) { return "Build Version Info"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1446585162 = messageFormatterFn((function(  ) {
  return function (d) { return "Comments"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a934345247 = messageFormatterFn((function(  ) {
  return function (d) { return "Company (optional)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a373570795 = messageFormatterFn((function(  ) {
  return function (d) { return "Feedback Type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a593900205 = messageFormatterFn((function(  ) {
  return function (d) { return "Submit Feedback"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1316804918 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn More"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1624927425 = messageFormatterFn((function(  ) {
  return function (d) { return "Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1589318453 = messageFormatterFn((function(  ) {
  return function (d) { return "How can we help you?"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a600089677 = messageFormatterFn((function(  ) {
  return function (d) { return "What do you like about this experience?"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a756262084 = messageFormatterFn((function(  ) {
  return function (d) { return "Explain what's happening and walk us through the problem."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1307327804 = messageFormatterFn((function(  ) {
  return function (d) { return "Unable to submit feedback."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1705121075 = messageFormatterFn((function(  ) {
  return function (d) { return "Thanks for your feedback!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1867204299 = messageFormatterFn((function(  ) {
  return function (d) { return "Please try again later."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b820624549 = messageFormatterFn((function(  ) {
  return function (d) { return "Submitting, Please Wait"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1572332605 = messageFormatterFn((function(  ) {
  return function (d) { return " was created to track your input."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1565332292 = messageFormatterFn((function(  ) {
  return function (d) { return "Feature Request"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b117477125 = messageFormatterFn((function(  ) {
  return function (d) { return "Praise"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a892839805 = messageFormatterFn((function(  ) {
  return function (d) { return "Problem"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b351682574 = messageFormatterFn((function(  ) {
  return function (d) { return "Aggregation / Group by"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2103619310 = messageFormatterFn((function(  ) {
  return function (d) { return "All Types"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a119611898 = messageFormatterFn((function(  ) {
  return function (d) { return "Boolean"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a41412312 = messageFormatterFn((function(  ) {
  return function (d) { return "Date"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1106288512 = messageFormatterFn((function(  ) {
  return function (d) { return "Geographic"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b997993891 = messageFormatterFn((function(  ) {
  return function (d) { return "Number"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1993591687 = messageFormatterFn((function(  ) {
  return function (d) { return "Text"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1205629817 = messageFormatterFn((function(  ) {
  return function (d) { return "At Least"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1523528443 = messageFormatterFn((function(  ) {
  return function (d) { return "At Most"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1726430695 = messageFormatterFn((function(  ) {
  return function (d) { return "Between"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b861786364 = messageFormatterFn((function(  ) {
  return function (d) { return "Accept"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1161565174 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a274527665 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn More"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2017368099 = messageFormatterFn((function(  ) {
  return function (d) { return "Bottom"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1018557107 = messageFormatterFn((function(  ) {
  return function (d) { return "Top"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1879872507 = messageFormatterFn((function(  ) {
  return function (d) { return "en_US"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a689824219 = messageFormatterFn((function(  ) {
  return function (d) { return "Delete"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a537429519 = messageFormatterFn((function(  ) {
  return function (d) { return "Duplicate"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a401166476 = messageFormatterFn((function(  ) {
  return function (d) { return "Adjust your question or clear all to start over"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1845802794 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data doesn't understand your request. Try rephrasing it, or choose a suggestion below."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1840867959 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data doesn't understand your request. Try another one."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1649338108 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask about fields in this data source"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1851944502 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask about fields in this data source (English only)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a888997542 = messageFormatterFn((function(  ) {
  return function (d) { return "Quantitative filter tabs"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b709148202 = messageFormatterFn((function(  ) {
  return function (d) { return "Restore " + d.numberOfSheets + " sheets from your previous session?"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a878947263 = messageFormatterFn((function(  ) {
  return function (d) { return "We’ve restored your previous session"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1157031528 = messageFormatterFn((function(  ) {
  return function (d) { return "No"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1518175926 = messageFormatterFn((function(  ) {
  return function (d) { return "Yes"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a976743757 = messageFormatterFn((function(  ) {
  return function (d) { return "Save as..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b791299247 = messageFormatterFn((function(  ) {
  return function (d) { return "Save (overwrites)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1526912219 = messageFormatterFn((function(  ) {
  return function (d) { return "Saved viz to workbook"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2077920133 = messageFormatterFn((function(  ) {
  return function (d) { return "Save..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1983300535 = messageFormatterFn((function(  ) {
  return function (d) { return "Alphabetical"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1206591921 = messageFormatterFn((function(  ) {
  return function (d) { return "Ascending"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1166966793 = messageFormatterFn((function(  ) {
  return function (d) { return "Descending"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1702866953 = messageFormatterFn((function(  ) {
  return function (d) { return "Clear All"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b805818496 = messageFormatterFn((function(  ) {
  return function (d) { return "Redo"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b780356801 = messageFormatterFn((function(  ) {
  return function (d) { return "Save"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1178777306 = messageFormatterFn((function(  ) {
  return function (d) { return "Swap Axes"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1568091506 = messageFormatterFn((function(  ) {
  return function (d) { return "Undo"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1798475645 = messageFormatterFn((function(  ) {
  return function (d) { return "Usage Analytics"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a3834001 = messageFormatterFn((function(  ) {
  return function (d) { return "View"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a638884461 = messageFormatterFn((function(  ) {
  return function (d) { return "Bar Chart"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b71033170 = messageFormatterFn((function(  ) {
  return function (d) { return "Gantt Chart"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1656314394 = messageFormatterFn((function(  ) {
  return function (d) { return "Heat Map"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1254859714 = messageFormatterFn((function(  ) {
  return function (d) { return "Histogram"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1810803649 = messageFormatterFn((function(  ) {
  return function (d) { return "Line Chart"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1102566201 = messageFormatterFn((function(  ) {
  return function (d) { return "Map"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a652039590 = messageFormatterFn((function(  ) {
  return function (d) { return "Pie Chart"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1917880553 = messageFormatterFn((function(  ) {
  return function (d) { return "Scatter Plot"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1257184486 = messageFormatterFn((function(  ) {
  return function (d) { return "Text Table"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1834070760 = messageFormatterFn((function(  ) {
  return function (d) { return "Treemap"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2137515519 = messageFormatterFn((function(  ) {
  return function (d) { return "No marks appear on this map because geographic data is either missing or incorrectly structured."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a242952675 = messageFormatterFn((function(  ) {
  return function (d) { return "Go back?"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1337114209 = messageFormatterFn((function(  ) {
  return function (d) { return "en_US"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b940541282 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask about fields in this data source"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b499469162 = messageFormatterFn((function(  ) {
  return function (d) { return "No data matches the filters for your question. "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b721910660 = messageFormatterFn((function(  ) {
  return function (d) { return "No records"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1995572388 = messageFormatterFn((function(  ) {
  return function (d) { return "Got it"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b115854839 = messageFormatterFn((function(  ) {
  return function (d) { return "Hover over dimensions and measures to see the data available to you. Use keywords you find here when framing your questions."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1709181592 = messageFormatterFn((function(  ) {
  return function (d) { return "Get to know your data"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1977344309 = messageFormatterFn((function(  ) {
  return function (d) { return "When you like the resulting viz, add phrases to further expand it."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1654516119 = messageFormatterFn((function(  ) {
  return function (d) { return "When you like the resulting viz, add phrases to further expand it.<br />Ask Data requires English analytical phrases but works great with non-English data sources."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1801726634 = messageFormatterFn((function(  ) {
  return function (d) { return "Start with simple questions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1990976261 = messageFormatterFn((function(  ) {
  return function (d) { return "Hover over phrases, and click underlined elements to quickly change fields and calculations."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b375147164 = messageFormatterFn((function(  ) {
  return function (d) { return "Refine questions with a click"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a650998047 = messageFormatterFn((function(  ) {
  return function (d) { return "Ask Data is unavailable at this time"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b145714089 = messageFormatterFn((function(  ) {
  return function (d) { return "Or try one of these suggestions:"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1942727245 = messageFormatterFn((function(  ) {
  return function (d) { return d.PROJECT_NAME; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a322493263 = messageFormatterFn((function(  ) {
  return function (d) { return "You do not have permission to move to “" + d.PROJECT_NAME + "”"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a849829004 = messageFormatterFn((function(  ) {
  return function (d) { return "Content cannot be moved to “" + d.PROJECT_NAME + "”"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b707568333 = messageFormatterFn((function(  ) {
  return function (d) { return d.SITE_NAME + " (site root)"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b256468981 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1133392248 = messageFormatterFn((function(  ) {
  return function (d) { return "Continue"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b290167621 = messageFormatterFn((function(  ) {
  return function (d) { return "Continue without signing in"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2021629502 = messageFormatterFn((function(  ) {
  return function (d) { return "Connect to " + d.DATA_SOURCE; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1323884826 = messageFormatterFn((function(  ) {
  return function (d) { return "Before you connect"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1942925832 = messageFormatterFn((function(  ) {
  return function (d) { return "Sign in with your " + d.DATA_SOURCE + " account to see the dashboard with your data, or continue without signing in to quickly see it with sample data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1237574269 = messageFormatterFn((function(  ) {
  return function (d) { return "Make sure you’re using the cloud-based version of ServiceNow and have permission to access the necessary data. When you sign in, use your ServiceNow credentials, which may differ from those you use for single sign-on."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1673713816 = messageFormatterFn((function(  ) {
  return function (d) { return "You must be a company Administrator"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1663350618 = messageFormatterFn((function(  ) {
  return function (d) { return " on your QuickBooks Online account to use Tableau to connect to QuickBooks Online."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a69096519 = messageFormatterFn((function(  ) {
  return function (d) { return "Only one Company Administrator per company"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1663349657 = messageFormatterFn((function(  ) {
  return function (d) { return " can use Tableau to connect to QuickBooks Online. If another Company Administrator has used Tableau, that administrator must give up the Tableau Online application privilege so that you can use them."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b245754859 = messageFormatterFn((function(  ) {
  return function (d) { return "Sign in to " + d.DATA_SOURCE + " to see your data in the dashboard. Or continue without signing in to see sample data."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a572292111 = messageFormatterFn((function(  ) {
  return function (d) { return "Create Parameter"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b796057599 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit Parameter"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b380121008 = messageFormatterFn((function(  ) {
  return function (d) { return "Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b965396537 = messageFormatterFn((function(  ) {
  return function (d) { return "Properties"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2028960704 = messageFormatterFn((function(  ) {
  return function (d) { return "Aliases"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1707846296 = messageFormatterFn((function(  ) {
  return function (d) { return "Data type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1946800442 = messageFormatterFn((function(  ) {
  return function (d) { return "Float"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b762084937 = messageFormatterFn((function(  ) {
  return function (d) { return "Integer"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b663290207 = messageFormatterFn((function(  ) {
  return function (d) { return "String"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a803887649 = messageFormatterFn((function(  ) {
  return function (d) { return "Boolean"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1561467876 = messageFormatterFn((function(  ) {
  return function (d) { return "Date"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b147498921 = messageFormatterFn((function(  ) {
  return function (d) { return "DateTime"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1290945164 = messageFormatterFn((function(  ) {
  return function (d) { return "Current value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1032591143 = messageFormatterFn((function(  ) {
  return function (d) { return "Allowable values"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a814593976 = messageFormatterFn((function(  ) {
  return function (d) { return "Range of values"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1793284123 = messageFormatterFn((function(  ) {
  return function (d) { return "All"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1156900099 = messageFormatterFn((function(  ) {
  return function (d) { return "List"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1704690096 = messageFormatterFn((function(  ) {
  return function (d) { return "Range"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1406788334 = messageFormatterFn((function(  ) {
  return function (d) { return "Add From Parameter"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1825521373 = messageFormatterFn((function(  ) {
  return function (d) { return "Add From Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b579381939 = messageFormatterFn((function(  ) {
  return function (d) { return "Paste From Clipboard"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b373888509 = messageFormatterFn((function(  ) {
  return function (d) { return "Set From Parameter"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1907494638 = messageFormatterFn((function(  ) {
  return function (d) { return "Set From Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b390040480 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a896017954 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a207983348 = messageFormatterFn((function(  ) {
  return function (d) { return "Years"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1202962175 = messageFormatterFn((function(  ) {
  return function (d) { return "Quarters"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b922461717 = messageFormatterFn((function(  ) {
  return function (d) { return "Months"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1563538467 = messageFormatterFn((function(  ) {
  return function (d) { return "Weeks"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b874578289 = messageFormatterFn((function(  ) {
  return function (d) { return "Days"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1689915411 = messageFormatterFn((function(  ) {
  return function (d) { return "Hours"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b359099139 = messageFormatterFn((function(  ) {
  return function (d) { return "Minutes"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1949817501 = messageFormatterFn((function(  ) {
  return function (d) { return "Seconds"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1044892251 = messageFormatterFn((function(  ) {
  return function (d) { return "Minimum"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a65546679 = messageFormatterFn((function(  ) {
  return function (d) { return "Maximum"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1211901814 = messageFormatterFn((function(  ) {
  return function (d) { return "Step size"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1503408096 = messageFormatterFn((function(  ) {
  return function (d) { return "Value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a503325244 = messageFormatterFn((function(  ) {
  return function (d) { return "Display As"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a433636253 = messageFormatterFn((function(  ) {
  return function (d) { return "Duplicate values found"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a332623435 = messageFormatterFn((function(  ) {
  return function (d) { return "Every value in the list must have a unique display name. Double-click the highlighted fields to update. Duplicate values will automatically be removed when you select OK."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b299983967 = messageFormatterFn((function(  ) {
  return function (d) { return d.alias + " is a duplicate"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1904455414 = messageFormatterFn((function(  ) {
  return function (d) { return "Remove Selected"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1188600784 = messageFormatterFn((function(  ) {
  return function (d) { return "Click to add"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a54530135 = messageFormatterFn((function(  ) {
  return function (d) { return "Show template project contributors!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b554486308 = messageFormatterFn((function(  ) {
  return function (d) { return "Hide template project contributors!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1032192403 = messageFormatterFn((function(  ) {
  return function (d) { return "Font family"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1290261712 = messageFormatterFn((function(  ) {
  return function (d) { return "Font size"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1140385221 = messageFormatterFn((function(  ) {
  return function (d) { return "Bold"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a127906416 = messageFormatterFn((function(  ) {
  return function (d) { return "Italic"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b701353968 = messageFormatterFn((function(  ) {
  return function (d) { return "Underline"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2039644186 = messageFormatterFn((function(  ) {
  return function (d) { return "Color"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1727521758 = messageFormatterFn((function(  ) {
  return function (d) { return "Left"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1033369644 = messageFormatterFn((function(  ) {
  return function (d) { return "Center"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1759424137 = messageFormatterFn((function(  ) {
  return function (d) { return "Right"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1411453506 = messageFormatterFn((function(  ) {
  return function (d) { return "Link"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1409474530 = messageFormatterFn((function(  ) {
  return function (d) { return "Text"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1486940408 = messageFormatterFn((function(  ) {
  return function (d) { return "Insert"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1062030329 = messageFormatterFn((function(  ) {
  return function (d) { return "Insert field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b60826821 = messageFormatterFn((function(  ) {
  return function (d) { return "Clear Formatting"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1887314314 = messageFormatterFn((function(  ) {
  return function (d) { return "Clear Formatting"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b269137057 = messageFormatterFn((function(  ) {
  return function (d) { return "Apply"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b730326866 = messageFormatterFn((function(  ) {
  return function (d) { return "Apply"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b973344233 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1131409766 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1143501173 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b394653372 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b729480610 = messageFormatterFn((function(  ) {
  return function (d) { return "Reset"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b738849811 = messageFormatterFn((function(  ) {
  return function (d) { return "Reset"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b988082435 = messageFormatterFn((function(  ) {
  return function (d) { return "Edit"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1944966956 = messageFormatterFn((function(  ) {
  return function (d) { return "Unlink"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a649940054 = messageFormatterFn((function(  ) {
  return function (d) { return "Show template project contributors!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a40923611 = messageFormatterFn((function(  ) {
  return function (d) { return "Hide template project contributors!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a509739462 = messageFormatterFn((function(  ) {
  return function (d) { return "On Data Refresh"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a347068190 = messageFormatterFn((function(  ) {
  return function (d) { return "Specified Time"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1954838669 = messageFormatterFn((function(  ) {
  return function (d) { return "Hourly"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1239665325 = messageFormatterFn((function(  ) {
  return function (d) { return "Daily"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1962846595 = messageFormatterFn((function(  ) {
  return function (d) { return "Weekly"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1512873313 = messageFormatterFn((function(  ) {
  return function (d) { return "Monthly"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a397210014 = messageFormatterFn((function(  ) {
  return function (d) { return "from " + d["1"] + " to " + d["2"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1492433292 = messageFormatterFn((function(  ) {
  return function (d) { return "at " + d["1"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a850303978 = messageFormatterFn((function(  ) {
  return function (d) { return d["1"] + " " + d["2"] + " " + d["4"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b912413145 = messageFormatterFn((function(  ) {
  return function (d) { return d["1"] + " " + d["2"] + " every " + d["3"] + " " + d["4"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b455527767 = messageFormatterFn((function(  ) {
  return function (d) { return d["1"] + " at " + d["2"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a965394059 = messageFormatterFn((function(  ) {
  return function (d) { return d["1"] + " " + d["2"] + " every " + d["3"] + " from " + d["4"] + " to " + d["5"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1288108565 = messageFormatterFn((function(  ) {
  return function (d) { return d["1"] + " " + d["2"] + " every " + d["3"] + " starting at " + d["4"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1527914641 = messageFormatterFn((function(  ) {
  return function (d) { return "days a week,"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1384732830 = messageFormatterFn((function(  ) {
  return function (d) { return "day a week,"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2076107680 = messageFormatterFn((function(  ) {
  return function (d) { return "to"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2035136165 = messageFormatterFn((function(  ) {
  return function (d) { return "Time zone"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1143469946 = messageFormatterFn((function(  ) {
  return function (d) { return "At time"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1232555827 = messageFormatterFn((function(  ) {
  return function (d) { return "At"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1068433092 = messageFormatterFn((function(  ) {
  return function (d) { return "From"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1231994603 = messageFormatterFn((function(  ) {
  return function (d) { return "To"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2020303977 = messageFormatterFn((function(  ) {
  return function (d) { return "Every"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1232144519 = messageFormatterFn((function(  ) {
  return function (d) { return "On"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1545015087 = messageFormatterFn((function(  ) {
  return function (d) { return "Day"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1211906938 = messageFormatterFn((function(  ) {
  return function (d) { return "First"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1715974668 = messageFormatterFn((function(  ) {
  return function (d) { return "Second"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1708743299 = messageFormatterFn((function(  ) {
  return function (d) { return "Third"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2094292454 = messageFormatterFn((function(  ) {
  return function (d) { return "Fourth"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1222970931 = messageFormatterFn((function(  ) {
  return function (d) { return "Fifth"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1814341418 = messageFormatterFn((function(  ) {
  return function (d) { return "Last"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1552946998 = messageFormatterFn((function(  ) {
  return function (d) { return "Half hour"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b188687689 = messageFormatterFn((function(  ) {
  return function (d) { return "Hour"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b400331149 = messageFormatterFn((function(  ) {
  return function (d) { return "Two hours"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b128945283 = messageFormatterFn((function(  ) {
  return function (d) { return "Four hours"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1833563254 = messageFormatterFn((function(  ) {
  return function (d) { return "Eight hours"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b950669136 = messageFormatterFn((function(  ) {
  return function (d) { return "Twelve hours"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a649660331 = messageFormatterFn((function(  ) {
  return function (d) { return "Sunday"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2047645419 = messageFormatterFn((function(  ) {
  return function (d) { return "Monday"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2108844504 = messageFormatterFn((function(  ) {
  return function (d) { return "Tuesday"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1447034097 = messageFormatterFn((function(  ) {
  return function (d) { return "Wednesday"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1563333323 = messageFormatterFn((function(  ) {
  return function (d) { return "Thursday"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a957272954 = messageFormatterFn((function(  ) {
  return function (d) { return "Friday"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b708468908 = messageFormatterFn((function(  ) {
  return function (d) { return "Saturday"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1942514855 = messageFormatterFn((function(  ) {
  return function (d) { return "S"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1366530713 = messageFormatterFn((function(  ) {
  return function (d) { return "M"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1512727626 = messageFormatterFn((function(  ) {
  return function (d) { return "T"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1832529119 = messageFormatterFn((function(  ) {
  return function (d) { return "W"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a195292509 = messageFormatterFn((function(  ) {
  return function (d) { return "Th"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1469360696 = messageFormatterFn((function(  ) {
  return function (d) { return "F"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a409286302 = messageFormatterFn((function(  ) {
  return function (d) { return "S"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b936157242 = messageFormatterFn((function(  ) {
  return function (d) { return d["1"] + " " + d["2"] + " at " + d["3"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b656595800 = messageFormatterFn((function(  ) {
  return function (d) { return d["1"] + d["2"] + " " + d["3"] + " at " + d["4"]; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1245593293 = messageFormatterFn((function(  ) {
  return function (d) { return "time a month"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a254545914 = messageFormatterFn((function(  ) {
  return function (d) { return "times a month"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b496796665 = messageFormatterFn((function(  ) {
  return function (d) { return "of the month"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b991252684 = messageFormatterFn((function(  ) {
  return function (d) { return "Repeats"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1008366748 = messageFormatterFn((function(  ) {
  return function (d) { return "Done"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1196396908 = messageFormatterFn((function(  ) {
  return function (d) { return "Show template project contributors!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1805413351 = messageFormatterFn((function(  ) {
  return function (d) { return "Hide template project contributors!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1077852668 = messageFormatterFn((function(  ) {
  return function (d) { return "Filter By"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b443006251 = messageFormatterFn((function(  ) {
  return function (d) { return "Sort By"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a434622246 = messageFormatterFn((function(  ) {
  return function (d) { return "Alphabetic"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2118864080 = messageFormatterFn((function(  ) {
  return function (d) { return "Data source order"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b952501343 = messageFormatterFn((function(  ) {
  return function (d) { return "Field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a603830175 = messageFormatterFn((function(  ) {
  return function (d) { return "Manual"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2139263024 = messageFormatterFn((function(  ) {
  return function (d) { return "Nested"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1476047259 = messageFormatterFn((function(  ) {
  return function (d) { return "Sort Order"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1088821292 = messageFormatterFn((function(  ) {
  return function (d) { return "Ascending"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1383025708 = messageFormatterFn((function(  ) {
  return function (d) { return "Descending"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1590542138 = messageFormatterFn((function(  ) {
  return function (d) { return "Aggregation"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1655818490 = messageFormatterFn((function(  ) {
  return function (d) { return "Clear"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1410814403 = messageFormatterFn((function(  ) {
  return function (d) { return "Field Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a787778813 = messageFormatterFn((function(  ) {
  return function (d) { return "Move up"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b599368426 = messageFormatterFn((function(  ) {
  return function (d) { return "Move down"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b955194377 = messageFormatterFn((function(  ) {
  return function (d) { return "Move to top"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b727685727 = messageFormatterFn((function(  ) {
  return function (d) { return "Move to bottom"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a131510542 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1261262676 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b202826446 = messageFormatterFn((function(  ) {
  return function (d) { return "True"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2027329707 = messageFormatterFn((function(  ) {
  return function (d) { return "False"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b595442054 = messageFormatterFn((function(  ) {
  return function (d) { return ","; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b370058622 = messageFormatterFn((function(  ) {
  return function (d) { return "b"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1222778765 = messageFormatterFn((function(  ) {
  return function (d) { return "m"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1355389397 = messageFormatterFn((function(  ) {
  return function (d) { return "p"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b2064395758 = messageFormatterFn((function(  ) {
  return function (d) { return "t"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a287782131 = messageFormatterFn((function(  ) {
  return function (d) { return "k"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1278458837 = messageFormatterFn((function(  ) {
  return function (d) { return "Parameter"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1300056718 = messageFormatterFn((function(  ) {
  return function (d) { return "Type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1563161741 = messageFormatterFn((function(  ) {
  return function (d) { return "Value"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2085797674 = messageFormatterFn((function(  ) {
  return function (d) { return "Sign in to reconnect"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1439999088 = messageFormatterFn((function(  ) {
  return function (d) { return "The username or password is not valid.  Check the database name and credentials and try again."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a676088830 = messageFormatterFn((function(  ) {
  return function (d) { return "Close"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1586131674 = messageFormatterFn((function(  ) {
  return function (d) { return "Close dialog"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b637250120 = messageFormatterFn((function(  ) {
  return function (d) { return "Custom color"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b593315275 = messageFormatterFn((function(  ) {
  return function (d) { return "Increment"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1570128473 = messageFormatterFn((function(  ) {
  return function (d) { return "Decrement"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1041600694 = messageFormatterFn((function(  ) {
  return function (d) { return "Wait indicator"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b426049886 = messageFormatterFn((function(  ) {
  return function (d) { return "Enter a valid date."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b248595313 = messageFormatterFn((function(  ) {
  return function (d) { return "Previous Month"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a909784723 = messageFormatterFn((function(  ) {
  return function (d) { return "Next Month"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a553908461 = messageFormatterFn((function(  ) {
  return function (d) { return "Week " + d.weekNum; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a505500216 = messageFormatterFn((function(  ) {
  return function (d) { return "No matches."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1541400977 = messageFormatterFn((function(  ) {
  return function (d) { return "Info: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1188078362 = messageFormatterFn((function(  ) {
  return function (d) { return "Success: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1893256685 = messageFormatterFn((function(  ) {
  return function (d) { return "Warning: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b295924671 = messageFormatterFn((function(  ) {
  return function (d) { return "Error: "; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1537425502 = messageFormatterFn((function(  ) {
  return function (d) { return "Use Dashboard"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a347884167 = messageFormatterFn((function(  ) {
  return function (d) { return "All data sources"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b737053074 = messageFormatterFn((function(  ) {
  return function (d) { return "Start from one of our pre-built dashboards. All you have to do is sign in to your data source."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b962698757 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1120231480 = messageFormatterFn((function(  ) {
  return function (d) { return "Create workbook"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1676883838 = messageFormatterFn((function(  ) {
  return function (d) { return "Create Workbook"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1379445792 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1734214183 = messageFormatterFn((function(  ) {
  return function (d) { return "Workbook name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1254004607 = messageFormatterFn((function(  ) {
  return function (d) { return "Select project"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a354889190 = messageFormatterFn((function(  ) {
  return function (d) { return "Creating workbook..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1851628779 = messageFormatterFn((function(  ) {
  return function (d) { return "If you're connecting to a lot of data, this could take some time. You'll receive an email when the dashboard is ready for you."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1016822261 = messageFormatterFn((function(  ) {
  return function (d) { return "Building an extract with your data..."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1389107356 = messageFormatterFn((function(  ) {
  return function (d) { return "If you're connecting to a lot of data, this could take some time. You'll receive an email when the dashboard is ready for you."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1456136672 = messageFormatterFn((function(  ) {
  return function (d) { return "For sensitive data, change permissions on the published workbook to adjust access."; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1279467625 = messageFormatterFn((function(  ) {
  return function (d) { return "Learn more"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b794508294 = messageFormatterFn((function(  ) {
  return function (d) { return "Got it"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1575499934 = messageFormatterFn((function(  ) {
  return function (d) { return "Available layouts"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1989638466 = messageFormatterFn((function(  ) {
  return function (d) { return "For use with"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1371265143 = messageFormatterFn((function(  ) {
  return function (d) { return "Rename Dashboard Item"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1261588545 = messageFormatterFn((function(  ) {
  return function (d) { return "OK"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1649480957 = messageFormatterFn((function(  ) {
  return function (d) { return "Cancel"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b297062076 = messageFormatterFn((function(  ) {
  return function (d) { return "Default Name"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1327931246 = messageFormatterFn((function(  ) {
  return function (d) { return "Clear All"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1474662360 = messageFormatterFn((function(  ) {
  return function (d) { return "Include"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b956442154 = messageFormatterFn((function(  ) {
  return function (d) { return "Sheet Selection"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1798555195 = messageFormatterFn((function(  ) {
  return function (d) { return "Select All"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b589710103 = messageFormatterFn((function(  ) {
  return function (d) { return d.x + " of " + d.y; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a118833521 = messageFormatterFn((function(  ) {
  return function (d) { return "Bin Size"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a468600943 = messageFormatterFn((function(  ) {
  return function (d) { return "Unknown"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1223258459 = messageFormatterFn((function(  ) {
  return function (d) { return "Calculated field"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b831977165 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return plural(d.count, 0, pluralFuncs.en, { one: function() { return d.formattedCount + " calculation";}, other: function() { return d.formattedCount + " calculations";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.b1251572056 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return plural(d.count, 0, pluralFuncs.en, { one: function() { return d.formattedCount + " user";}, other: function() { return d.formattedCount + " users";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.b901008999 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return plural(d.count, 0, pluralFuncs.en, { one: function() { return d.formattedCount + " workbook";}, other: function() { return d.formattedCount + " workbooks";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.a673646539 = messageFormatterFn((function(  ) {
  return function (d) { return "Connection"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1712397792 = messageFormatterFn((function(  ) {
  return function (d) { return "Continuous dimension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b146645032 = messageFormatterFn((function(  ) {
  return function (d) { return "Continuous measure"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1537564706 = messageFormatterFn((function(  ) {
  return function (d) { return "Database column"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a490091461 = messageFormatterFn((function(  ) {
  return function (d) { return "Description"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b291513986 = messageFormatterFn((function(  ) {
  return function (d) { return "Detail"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1959212150 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return plural(d.count, 0, pluralFuncs.en, { one: function() { return d.formattedCount + " dimension";}, other: function() { return d.formattedCount + " dimensions";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.a1789413626 = messageFormatterFn((function(  ) {
  return function (d) { return "Dimensions"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b343268490 = messageFormatterFn((function(  ) {
  return function (d) { return "Discrete dimension"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1816788654 = messageFormatterFn((function(  ) {
  return function (d) { return "Discrete measure"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b163980446 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return plural(d.count, 0, pluralFuncs.en, { one: function() { return d.formattedCount + " field";}, other: function() { return d.formattedCount + " fields";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.b939022929 = messageFormatterFn((function(  ) {
  return function (d) { return "Formula"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1912890376 = messageFormatterFn((function(  ) {
  return function (d) { return "Group"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b829864383 = messageFormatterFn((function(  ) {
  return function (d) { return "Groups"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1121004738 = messageFormatterFn((function(  ) {
  return function (d) { return "Hierarchy"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b611162624 = messageFormatterFn((function(  ) {
  return function (d) { return "Invalid"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b985486850 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return plural(d.count, 0, pluralFuncs.en, { one: function() { return d.formattedCount + " measure";}, other: function() { return d.formattedCount + " measures";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.a1946927746 = messageFormatterFn((function(  ) {
  return function (d) { return "Measures"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b649800674 = messageFormatterFn((function( plural, pluralFuncs ) {
  return function (d) { return plural(d.count, 0, pluralFuncs.en, { one: function() { return d.formattedCount + " member";}, other: function() { return d.formattedCount + " members";} }); }
})(messageFormat.plural, {"en": Globalize("en").pluralGenerator()}), Globalize("en").pluralGenerator({}));
Globalize.b1426588510 = messageFormatterFn((function(  ) {
  return function (d) { return "Members"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a295760455 = messageFormatterFn((function(  ) {
  return function (d) { return "No fields"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a35692585 = messageFormatterFn((function(  ) {
  return function (d) { return "Remote column"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b873176861 = messageFormatterFn((function(  ) {
  return function (d) { return "Role"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a526653611 = messageFormatterFn((function(  ) {
  return function (d) { return "Set"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b853531138 = messageFormatterFn((function(  ) {
  return function (d) { return "Sets"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b17552161 = messageFormatterFn((function(  ) {
  return function (d) { return "Status"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1254986769 = messageFormatterFn((function(  ) {
  return function (d) { return "Summary"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b806564185 = messageFormatterFn((function(  ) {
  return function (d) { return "Type"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1623009389 = messageFormatterFn((function(  ) {
  return function (d) { return "Unknown"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1468312234 = messageFormatterFn((function(  ) {
  return function (d) { return "Usage"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1850708549 = messageFormatterFn((function(  ) {
  return function (d) { return "Valid"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a132602575 = messageFormatterFn((function(  ) {
  return function (d) { return "Howdy World!"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1051889257 = messageFormatterFn((function(  ) {
  return function (d) { return "⌃"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b789717448 = messageFormatterFn((function(  ) {
  return function (d) { return "Ctrl+"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b32342593 = messageFormatterFn((function(  ) {
  return function (d) { return "⌥"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1663098756 = messageFormatterFn((function(  ) {
  return function (d) { return "Alt+"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1647124622 = messageFormatterFn((function(  ) {
  return function (d) { return "⇧"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b817358819 = messageFormatterFn((function(  ) {
  return function (d) { return "Shift+"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b611620386 = messageFormatterFn((function(  ) {
  return function (d) { return "Win+"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1893362522 = messageFormatterFn((function(  ) {
  return function (d) { return "⌘"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210531364 = messageFormatterFn((function(  ) {
  return function (d) { return "A"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210530403 = messageFormatterFn((function(  ) {
  return function (d) { return "B"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210529442 = messageFormatterFn((function(  ) {
  return function (d) { return "C"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210528481 = messageFormatterFn((function(  ) {
  return function (d) { return "D"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210527520 = messageFormatterFn((function(  ) {
  return function (d) { return "E"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210526559 = messageFormatterFn((function(  ) {
  return function (d) { return "F"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210525598 = messageFormatterFn((function(  ) {
  return function (d) { return "G"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210524637 = messageFormatterFn((function(  ) {
  return function (d) { return "H"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210523676 = messageFormatterFn((function(  ) {
  return function (d) { return "I"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210522715 = messageFormatterFn((function(  ) {
  return function (d) { return "J"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210521754 = messageFormatterFn((function(  ) {
  return function (d) { return "K"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210520793 = messageFormatterFn((function(  ) {
  return function (d) { return "L"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210519832 = messageFormatterFn((function(  ) {
  return function (d) { return "M"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210518871 = messageFormatterFn((function(  ) {
  return function (d) { return "N"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210517910 = messageFormatterFn((function(  ) {
  return function (d) { return "O"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210516949 = messageFormatterFn((function(  ) {
  return function (d) { return "P"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210515988 = messageFormatterFn((function(  ) {
  return function (d) { return "Q"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210515027 = messageFormatterFn((function(  ) {
  return function (d) { return "R"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210514066 = messageFormatterFn((function(  ) {
  return function (d) { return "S"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210513105 = messageFormatterFn((function(  ) {
  return function (d) { return "T"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210512144 = messageFormatterFn((function(  ) {
  return function (d) { return "U"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210511183 = messageFormatterFn((function(  ) {
  return function (d) { return "V"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210510222 = messageFormatterFn((function(  ) {
  return function (d) { return "W"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210509261 = messageFormatterFn((function(  ) {
  return function (d) { return "X"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210508300 = messageFormatterFn((function(  ) {
  return function (d) { return "Y"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1210507339 = messageFormatterFn((function(  ) {
  return function (d) { return "Z"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1151432803 = messageFormatterFn((function(  ) {
  return function (d) { return "Zero"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a645688231 = messageFormatterFn((function(  ) {
  return function (d) { return "One"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a650583565 = messageFormatterFn((function(  ) {
  return function (d) { return "Two"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2015886175 = messageFormatterFn((function(  ) {
  return function (d) { return "Three"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1714688357 = messageFormatterFn((function(  ) {
  return function (d) { return "Four"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1720212185 = messageFormatterFn((function(  ) {
  return function (d) { return "Five"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a649251619 = messageFormatterFn((function(  ) {
  return function (d) { return "Six"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1046197774 = messageFormatterFn((function(  ) {
  return function (d) { return "Seven"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1606807056 = messageFormatterFn((function(  ) {
  return function (d) { return "Eight"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1491417305 = messageFormatterFn((function(  ) {
  return function (d) { return "Nine"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a436141888 = messageFormatterFn((function(  ) {
  return function (d) { return "F1"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a436142849 = messageFormatterFn((function(  ) {
  return function (d) { return "F2"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a436143810 = messageFormatterFn((function(  ) {
  return function (d) { return "F3"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a436144771 = messageFormatterFn((function(  ) {
  return function (d) { return "F4"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a436145732 = messageFormatterFn((function(  ) {
  return function (d) { return "F5"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a436146693 = messageFormatterFn((function(  ) {
  return function (d) { return "F6"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a436147654 = messageFormatterFn((function(  ) {
  return function (d) { return "F7"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a436148615 = messageFormatterFn((function(  ) {
  return function (d) { return "F8"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a436149576 = messageFormatterFn((function(  ) {
  return function (d) { return "F9"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a635508358 = messageFormatterFn((function(  ) {
  return function (d) { return "F10"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a635509319 = messageFormatterFn((function(  ) {
  return function (d) { return "F11"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a635510280 = messageFormatterFn((function(  ) {
  return function (d) { return "F12"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1761867289 = messageFormatterFn((function(  ) {
  return function (d) { return "Enter"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1506255486 = messageFormatterFn((function(  ) {
  return function (d) { return "↵"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1796047699 = messageFormatterFn((function(  ) {
  return function (d) { return "/"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1213899343 = messageFormatterFn((function(  ) {
  return function (d) { return "↓"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1661496268 = messageFormatterFn((function(  ) {
  return function (d) { return "Down arrow"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b994602026 = messageFormatterFn((function(  ) {
  return function (d) { return "←"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1880793585 = messageFormatterFn((function(  ) {
  return function (d) { return "Left arrow"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a377322755 = messageFormatterFn((function(  ) {
  return function (d) { return "→"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b679726520 = messageFormatterFn((function(  ) {
  return function (d) { return "Right arrow"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b58858902 = messageFormatterFn((function(  ) {
  return function (d) { return "↑"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a770947909 = messageFormatterFn((function(  ) {
  return function (d) { return "Up arrow"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b432852224 = messageFormatterFn((function(  ) {
  return function (d) { return "Backspace"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1550509729 = messageFormatterFn((function(  ) {
  return function (d) { return "CapsLock"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a9246422 = messageFormatterFn((function(  ) {
  return function (d) { return "Comma"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1523725164 = messageFormatterFn((function(  ) {
  return function (d) { return "Menu"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1708958560 = messageFormatterFn((function(  ) {
  return function (d) { return "Delete"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a636452060 = messageFormatterFn((function(  ) {
  return function (d) { return "End"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1470654580 = messageFormatterFn((function(  ) {
  return function (d) { return "Equals"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1431166449 = messageFormatterFn((function(  ) {
  return function (d) { return "Plus"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1564524362 = messageFormatterFn((function(  ) {
  return function (d) { return "Escape"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1657680876 = messageFormatterFn((function(  ) {
  return function (d) { return "Home"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1431033070 = messageFormatterFn((function(  ) {
  return function (d) { return "Insert"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1227619198 = messageFormatterFn((function(  ) {
  return function (d) { return "Slash"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b601872153 = messageFormatterFn((function(  ) {
  return function (d) { return "Asterisk"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1784945145 = messageFormatterFn((function(  ) {
  return function (d) { return "Dash"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a721826182 = messageFormatterFn((function(  ) {
  return function (d) { return "PageDown"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1748739967 = messageFormatterFn((function(  ) {
  return function (d) { return "PageUp"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1323165174 = messageFormatterFn((function(  ) {
  return function (d) { return "Period"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1341656263 = messageFormatterFn((function(  ) {
  return function (d) { return "Space"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a649915670 = messageFormatterFn((function(  ) {
  return function (d) { return "Tab"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a2038944409 = messageFormatterFn((function(  ) {
  return function (d) { return "Tilde"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1100111879 = messageFormatterFn((function(  ) {
  return function (d) { return "Backtick"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a575931931 = messageFormatterFn((function(  ) {
  return function (d) { return "Exclamation mark"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a490734853 = messageFormatterFn((function(  ) {
  return function (d) { return "@"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1330686771 = messageFormatterFn((function(  ) {
  return function (d) { return "Pound"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1130080718 = messageFormatterFn((function(  ) {
  return function (d) { return "$"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1306444771 = messageFormatterFn((function(  ) {
  return function (d) { return "%"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b387164156 = messageFormatterFn((function(  ) {
  return function (d) { return "Caret"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1389384074 = messageFormatterFn((function(  ) {
  return function (d) { return "&"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b319168915 = messageFormatterFn((function(  ) {
  return function (d) { return "Open parenthesis"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b591022157 = messageFormatterFn((function(  ) {
  return function (d) { return "Close parenthesis"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1214674001 = messageFormatterFn((function(  ) {
  return function (d) { return "Underscore"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a161654282 = messageFormatterFn((function(  ) {
  return function (d) { return "Open brace"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1350855632 = messageFormatterFn((function(  ) {
  return function (d) { return "Close brace"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b218490206 = messageFormatterFn((function(  ) {
  return function (d) { return "Open square bracket"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a523549288 = messageFormatterFn((function(  ) {
  return function (d) { return "Close square bracket"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b460137484 = messageFormatterFn((function(  ) {
  return function (d) { return "Open angle bracket"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b297653394 = messageFormatterFn((function(  ) {
  return function (d) { return "Close angle bracket"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b368172024 = messageFormatterFn((function(  ) {
  return function (d) { return "Question mark"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a463133397 = messageFormatterFn((function(  ) {
  return function (d) { return "Single quote"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b1662449876 = messageFormatterFn((function(  ) {
  return function (d) { return "Double quote"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a8394976 = messageFormatterFn((function(  ) {
  return function (d) { return "Colon"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a1174068914 = messageFormatterFn((function(  ) {
  return function (d) { return "Semicolon"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.a866172478 = messageFormatterFn((function(  ) {
  return function (d) { return "Vertical bar"; }
})(), Globalize("en").pluralGenerator({}));
Globalize.b546889289 = messageFormatterFn((function(  ) {
  return function (d) { return "Backslash"; }
})(), Globalize("en").pluralGenerator({}));
}));
