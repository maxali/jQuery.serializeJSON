jQuery.fn.extend({
  serializeJSON: function() {
      var sArray = $(this).serializeArray();
      var jData = {};
      $.map(sArray, function(n, i){
          jData[n['name']] = n['value'];
      });
      return jData;
  }
})
