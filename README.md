[![Build Status](https://api.travis-ci.org/wimbervoets/material-two-stage-rating.svg)](https://travis-ci.org/wimbervoets/material-two-stage-rating)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/8d2be3003a2244fb8bef6fd91b9fd87e)](https://www.codacy.com/app/wimbervoets/material-two-stage-rating?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=wimbervoets/MaterialTwoStageRating&amp;utm_campaign=Badge_Grade)
[![GitHub license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/wimbervoets/material-two-stage-rating/blob/master/LICENSE)
[![Download](https://img.shields.io/badge/Sonatype%20OSSRH-1.0.2-brightgreen.svg)](https://oss.sonatype.org/#nexus-search;gav~be.jatra~materialtwostagerating~1.0.2~~)

# Material Two Stage Rating
"Material Two Stage Rating" is a library to help you promote your android app by prompting users to rate the app after using it for a few days.
Also its two stage process ensures higher reviews to go to playstore while getting useful feedback on lower ratings.


# Screenshots and stages

<img src="https://github.com/wimbervoets/material-two-stage-rating/blob/master/snapshots/device-2017-03-29-214628.png" width="200" height="350" /><br/>
<img src="https://github.com/wimbervoets/material-two-stage-rating/blob/master/snapshots/device-2017-03-29-214713.png" width="200" height="350" />
<img src="https://github.com/wimbervoets/material-two-stage-rating/blob/master/snapshots/device-2017-03-29-214753.png" width="200" height="350" />
<img src="https://github.com/wimbervoets/material-two-stage-rating/blob/master/snapshots/device-2017-03-29-214859.png" width="200" height="350" /><br/>
<img src="https://github.com/wimbervoets/material-two-stage-rating/blob/master/snapshots/device-2017-03-29-215033.png" width="200" height="350" />
<img src="https://github.com/wimbervoets/material-two-stage-rating/blob/master/snapshots/device-2017-03-29-215120.png" width="200" height="350" />
<img src="https://github.com/wimbervoets/material-two-stage-rating/blob/master/snapshots/device-2017-03-29-215231.png" width="200" height="350" />

# Install

Go to your project's build.gradle, and add the Maven OSS Releases repository:

    maven { url "https://oss.sonatype.org/content/repositories/releases/" }

Go to your app's build.gradle file and inside dependencies{} add :

     compile 'be.jatra:materialtwostagerating:1.0.2'

#  Usage

Put this one liner in the onCreate() method of your activity:
```java
	MaterialTwoStageRating.with(this).showIfMeetsConditions();
```

# Apps using Material Two Stage Rating

* [Makota Money Manager](https://play.google.com/store/apps/details?id=be.jatra.makota)

# Contribute
Contributions are welcome. Please open a [pull-request](https://help.github.com/articles/about-pull-requests/).

# Credits

* [Shailesh Mamgain](https://github.com/shaileshmamgain5/TwoStageRate)


# Developed By

* Wim Bervoets
  * [about.me/wbervoets](https://about.me/wbervoets)
  * [paypal.me/wimbervoets](https://www.paypal.me/wimbervoets)


# License

    Copyright 2017 Wim Bervoets

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



