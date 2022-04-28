# react-native-pickerview
关于Android时间选择的自定义语言封装(中英文)
集成：在RN端引用 

const RNPickerView = requireNativeComponent('RNPickerView', Picker);
      //传入对应参数
      <RNPickerView
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
