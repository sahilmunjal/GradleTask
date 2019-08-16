# GradleTask
GradleTask is an Android project in which build distribution is done using Gradle Custom Tasks.

In this, after release build creation it is uploaded on Diawi using its REST API's and then link for that build is send to other people like testers, etc using mailgun REST API's.

We can pass the email Ids while running the gradle task like this :
```gradle

./gradlew buildReleaseApk -Pemail=<-- email Ids seperated with commas and no space -->
```
**OR**

we can simply run the task without param and it will pick the default email Ids mentioned in gradle file.
```gradle

./gradlew buildReleaseApk
```

## LICENSE
<br>
<pre><code>Copyright 2019 Sahil Munjal

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

</code></pre>
