关于Android时间选择的自定义语言封装(中英文)

android

1、引入pickerview至项目

2、在项目的build.gradle中implementation project(":pickerview")

3、MainApplication中添加PickerPackage

React-Native

1、const RNPickerView = requireNativeComponent('RNPickerView', Picker);

  //传入对应参数
2、 <RNPickerView

    style={styles.picker}
                
    minYear={minYear}
                
    maxYear={maxYear}
                
    datePickerMode={datePickerMode}
                
    defaultTime={defaultDateTime}
                
    title={title}
                
    languageType={currentLanguage}
                
    config={dataTime}
                
    onPickerConfirm={event => Confirm(event.nativeEvent.data)}
  
    onPickerCancel={event => Cancel(event.nativeEvent.data)}
  
  />
