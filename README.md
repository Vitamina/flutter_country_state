# flutter_country_state

A customizable Flutter package that displays all countries with there respective states.




## Example

 Please run the app in the [Example](https://github.com/mimi-tech/flutter_country_state/tree/master/example) folder

## Installation
* add the dependency to your [pubspec.yaml](https://github.com/mimi-tech/flutter_country_state/tree/master/pubspec.yaml) file.
```
dependencies:
  flutter:
    sdk: flutter
  flutter_country_state:
  ```
<table>
<tr>
<td>
<img src="https://user-images.githubusercontent.com/62711340/151657235-c2788bb1-3e8b-4395-95be-12835d989aac.jpeg" height="600" width="600">

</td>

<td>
<img src="https://user-images.githubusercontent.com/62711340/151657287-775c8cc9-6c90-48be-a6d2-97c9876ee577.jpeg" height="600" width="600">
</td>
</tr>
</table>


<table>
<tr>
<td>
<img src="https://user-images.githubusercontent.com/62711340/151657556-b4e075c4-3fc6-4ae1-88b1-6bf8abf5be19.jpeg" height="600" width="600">

</td>

<td>
<img src="https://user-images.githubusercontent.com/62711340/151657580-90a57249-78ea-4767-9c31-ecab5fcd6de8.jpeg" height="600" width="600">
</td>
</tr>
</table>



 ### You can also change the style of the text of list of the country and states
<p>-searchHint</p>
<p>-substringBackground</p>
<p>-textColors</p>
<p>-substringTextColor</p>
<p>-substringFontSize</p>
<p>-fontStyle</p>


<hr>
 
 ## Use It
 ### This will display the countries; You can display the country and state either with bottom sheet or dialog
  ``` dart
 ShowMyDialog(
searchHint: 'Search country',
substringBackground: Colors.green,
textColors: Colors.black,
substringTextColor: Colors.white,
fontSize: 18,
substringFontSize: 14,
fontFamily: '',
fontStyle: FontStyle.normal,
)
```
### This will display the states of the country selected
 ``` dart
StateDialog(
substringTextColor: Colors.white,
fontSize: 18,
textColors: Colors.black,
substringFontSize: 14,
fontFamily: '',
fontStyle: FontStyle.normal,
substringBackground: Colors.blueAccent,
),
```

## Next goal
- [ x ] Add countries flag 
- [ x ] Add countries code

