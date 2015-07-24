
describe( "wyswig-editor", function() {
   

   it( "should have proper default text value", function() {
      var React = require( "react/addons" );
      //var ContentEditable = require("../wysiwyg-editor/lib/content-editable/content-editable.js");

      
      var TestUtils = React.addons.TestUtils;
      var yellow = document.getElementById("contenteditable").innerHTML;
      console.log(yellow);
      var x = document.getElementsByTagName("p")[0].childNodes[0].nodeValue;
      
      //console.log("cokolwiek");
      var green = document.getElementsByClassName("wysiwyg-editor");
      var x = document.getElementsByTagName("p")[0].childNodes[0].nodeValue;
      console.log("cokolwiek, cos tam cos tam" + x);

      console.log(green);
      /*var border = green.getAttribute("border");
      console.log("it should print whats the border attribute of that element??" + border);*/


      //var contentEditableComponent = TestUtils.findRenderedDOMComponentWithClass( ContentEditable, "content-editable" );
      var grey = document.getElementsByClassName("icon-link");
      console.log("tutaj niby ten guzik ktory dodaje URL on text" + grey);

      
      



      





      assert.equal(yellow, "<p>لان في, علعلعلعلعلعلعلعل فكان الجوي وحرمان</p>");

      // Render a wyswigeditor
      //var wyswigEditor = TestUtils.renderIntoDocument(
        // React.createElement(DemoWysiwygEditor, null)
         
      //);

      //var contentEditableComponent = TestUtils.findRenderedDOMComponentWithClass( wyswigEditor, "content-editable" );
      //var contentEditableValue = contentEditableComponent.getDOMNode().innerHTML;

      //assert.equal( "000" + contentEditableValue + "000", '000<p>لان في, علعلعلعلعلعلعلعل فكان الجوي وحرمان</p>000' );
   });
it( "adding text to content-editable", function() {
      var React = require( "react/addons" );
      //var ContentEditable = require("../wysiwyg-editor/lib/content-editable/content-editable.js");

      
      var TestUtils = React.addons.TestUtils;
      var yellow = document.getElementById("contenteditable").innerHTML;
      var yellowChanged = yellow.replace(yellow, yellow + "TEST");
      console.log(yellowChanged);


      





      assert.equal(yellowChanged, "<p>لان في, علعلعلعلعلعلعلعل فكان الجوي وحرمان</p>TEST");

      // Render a wyswigeditor
      //var wyswigEditor = TestUtils.renderIntoDocument(
        // React.createElement(DemoWysiwygEditor, null)
         
      //);

      //var contentEditableComponent = TestUtils.findRenderedDOMComponentWithClass( wyswigEditor, "content-editable" );
      //var contentEditableValue = contentEditableComponent.getDOMNode().innerHTML;

      //assert.equal( "000" + contentEditableValue + "000", '000<p>لان في, علعلعلعلعلعلعلعل فكان الجوي وحرمان</p>000' );
   });


it( "should handle add link", function( done ) {
      

      var grey = document.getElementsByClassName("icon-link");
      console.log("tutaj niby ten guzik ktory dodaje URL on text" + grey);

      var y = document.getElementsByTagName("p")[0].childNodes[0].nodeValue;
      console.log("Poland Alkoholand    " + y);

      
    
    var linkUrlValue ='<a href="wp.pl" target="_blank">L</a>';
    var textAreaValue = "<p>لان في, علعلعلعلعلعلعلعل فكان الجوي وحرمان";
    var addedText = "LLLLLLLLLLLLLLLLLLLLLLL</p>";
    var newTextAreaValue = textAreaValue + linkUrlValue + addedText;
    console.log(newTextAreaValue);
    console.log('<p>لان في, علعلعلعلعلعلعلعل فكان الجوي وحرمان<a href="wp.pl" target="_blank">L</a>LLLLLLLLLLLLLLLLLLLLLLL</p>');
    
    // OK we have already inserted <a href="http://xyz"></a> tags,

    /*handleAddLink: function handleAddLink() {
    var wyswigAreaNode = React.findDOMNode(this.refs.wyswigArea);
    var linkInputNode = React.findDOMNode(this.refs.linkInput);
    var linkUrlValue = linkInputNode.value;
    var textAreaValue = this.getContentProperly();
    var posObj = this.state.contentEditablePos;

    var startTag = "<a href=\"" + linkUrlValue + "\" target=\"_blank\">";
    var endTag = "</a>";
    var newTextAreaValue = this.replaceWithTags(startTag, endTag, posObj, textAreaValue);

    // OK we have already inserted <a href="http://xyz"></a> tags,
    this.onChangeText(newTextAreaValue);
    this.closeDialog();
  },*/
     assert.equal(newTextAreaValue, '<p>لان في, علعلعلعلعلعلعلعل فكان الجوي وحرمان<a href="wp.pl" target="_blank">L</a>LLLLLLLLLLLLLLLLLLLLLLL</p>');

      

     
    });




});
  


/*it( "using Add an URL on text", function( done ) {
      this.timeout( 700 );
      var React = require( "react/addons" );
      var DemoWysiwygEditor = require( "../wysiwyg-editor/demo/dist/js/index.js" );
      var TestUtils = React.addons.TestUtils;

      // Render a wyswigeditor
      var wyswigEditor = TestUtils.renderIntoDocument(
         <DemoWysiwygEditor />
      );
       //var wyswigAreaNode = React.findDOMNode( this.refs.wyswigArea );

       var contentEditableComponent = TestUtils.findRenderedDOMComponentWithClass( wyswigEditor, "" );

       var contentEditableNode = contentEditableComponent.React.findDOMNode();

       React.addons.TestUtils.Simulate.focus( contentEditableNode );

       contentEditableNode.selectionStart = 3;
       contentEditableNode.selectionEnd = 5;

       setTimeout( function() {
          var showLinkInputButton = TestUtils.findRenderedDOMComponentWithClass( wyswigEditor, "icon-link" );
          var showLinkInputButtonNode = showLinkInputButton.React.findDOMNode();
          React.addons.TestUtils.Simulate.click( showLinkInputButtonNode );

          var linkInputNode = TestUtils.findRenderedDOMComponentWithClass( wyswigEditor, "link-input" ).React.findDOMNode();
          linkInputNode.value = "http://google.com";

          var addLinkNode = TestUtils.findRenderedDOMComponentWithClass( wyswigEditor, "add-link" ).React.findDOMNode();
          React.addons.TestUtils.Simulate.click( addLinkNode );

          assert.equal( contentEditableNode.value, "لان‪<a href=\"http://google.com\" target=\"_blank\">‫ ف‬</a>‬ي, عل فكان الجوي وحرمان");
          done();
       }, 300 );
    });

*/



