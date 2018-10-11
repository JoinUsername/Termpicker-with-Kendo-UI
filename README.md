# Termpicker-with-Kendo-UI

dropdownlist
https://demos.telerik.com/kendo-ui/dropdownlist/virtualization

<pre>
<!DOCTYPE html>
<html>
<head>
    <title></title>
    <link rel="stylesheet" href="https://kendo.cdn.telerik.com/2018.3.911/styles/kendo.common.min.css" />
    <link rel="stylesheet" href="https://kendo.cdn.telerik.com/2018.3.911/styles/kendo.default.min.css" />
    <link rel="stylesheet" href="https://kendo.cdn.telerik.com/2018.3.911/styles/kendo.default.mobile.min.css" />

    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://kendo.cdn.telerik.com/2018.3.911/js/kendo.all.min.js"></script>
    <script src="https://kendo.cdn.telerik.com/2018.3.911/js/kendo.timezones.min.js"></script>

</head>
<body>
  <div id="container">
      <span class="k-widget k-tooltip k-tooltip-validation k-invalid-msg" for="error" style="display: none;"></span>
      <label for="client-container">Employer</label>
      <div id="client-container">
        <svg class="loadinganim"><use xlink:href="#refresh"></use></svg>
      </div>
  </div>
  
  <svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
      <symbol id="refresh" viewBox="0 0 408 408">
          <title>refresh</title>
          <path fill="#37a42c" d="M0,204c0,56.1,22.95,107.1,61.2,142.8L0,408h153V255l-56.1,56.1C68.85,285.6,51,247.35,51,204 c0-66.3,43.35-122.4,102-145.35v-51C66.3,30.6,0,109.65,0,204z M408,0H255v153l56.1-56.1C339.15,122.4,357,160.65,357,204 c0,66.3-43.35,122.4-102,145.35V402.9c86.7-22.95,153-102,153-196.351c0-56.1-22.95-107.1-61.2-142.8L408,0z"></path>
      </symbol>
  </svg>
</body>
</html>
</pre>
