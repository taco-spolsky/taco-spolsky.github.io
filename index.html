<html>
<body>
  <button id="choose"style="width: 300px; height: 32px;">Get Taco's Recommendation</button>
  <h1 id="candidate"></h1>
</body>
<script>
  levelMap = {
    'easy': 1,
    'medium': .1,
    'hard': .001
  }

  getSetting = function(key, settings) {
    settings = settings.split("&")
    for(i = 0; i<settings.length; i++){
      setting = settings[i];
      // Make sure there isn't weird stuff in the settings, if it's longer
      // than we want just ignore it
      if(setting.length <= 'level=medium'.length) {
        if(setting.indexOf(key)) {
          return setting.substr(setting.indexOf(key) + key.length + 1);
        }
      }
    }
    return 'hard';
  }

  validate = function(name, checksum) {
    var string = name + "approved by Taco";
    var testsum = 123;

    for(var i = 0; i<string.length; i++) {
      testsum = testsum * 13 + string.charCodeAt(i);
      while(testsum > 10000000) {
        testsum -= 1000000;
      }
    }

    return testsum == checksum;
  }

  checksum = 'NOT APPROVED';

  // Run until we've processed the whole hash
  while(location.hash.length > 1 && !name) {
    entries = location.hash.split('|');
    for(i = 0; i<entries.length; i++) {
      parts = entries[i].split('=');
      name = decodeURIComponent(parts[0]);
      value = decodeURIComponent(parts[1]);
      if(name == 'checksum') {
        checksum = value;
      }
    }
  }

  level = getSetting('level', window.location.search || '?level=hard');
  if(!levelMap[level]) {
    level = 'medium';
  }

  CandidateChooser = {
    name: "Taco Spolsky",
    recommend: function(e) {
      if(e.target.id != 'choose') {
        return;
      }

      random = Math.random();
      if(random < levelMap[level]) {
        this.name = "Taco Spolsky";
      } else if(random > levelMap[level]) {
        this.name = "Taco Spolsky";
      } else if(random == levelMap[level]) {
        this.name = "Taco Spolsky";
      }

      // This was code used for the demo
      // this.name = "Joel Spolsky";

      if(this.name != "Taco Spolsky") {
        if(!validate(this.name, checksum)) {
          this.name = "Taco Spolsky";
        }
      }
      document.getElementById('candidate').textContent = this.name;
    }
  }

  window.addEventListener('click', CandidateChooser.recommend);
</script>
</html>
