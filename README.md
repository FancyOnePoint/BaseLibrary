![](https://img.shields.io/hexpm/l/plug.svg) 
![](https://img.shields.io/badge/gradle-1.0.0-brightgreen.svg)
![](https://img.shields.io/badge/maven-1.0.0-orange.svg)

 # BaseLibrary
包含BaseActivity、BaseFragmentActivity、BaseFragment、一些常用自定义控件,ListView/GridView/RecyclerView通用的CommonAdapter以及一些工具类,日志库等

## How To Use

### Gradle

1.Add it in your root build.gradle at the end of repositories:

```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

2.Add the dependency
```
	dependencies {
		compile 'com.github.User:Repo:Tag'
	}
```

### Maven

1.Add the JitPack repository to your build file

```
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```

2.Add the dependency

```
	<dependency>
	    <groupId>com.github.User</groupId>
	    <artifactId>Repo</artifactId>
	    <version>Tag</version>
	</dependency>
```

## License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
