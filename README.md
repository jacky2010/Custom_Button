# Custom Button

## b1 : 5 file xml gồm
+ button_disabled.xml 
+ button_enabled.xml 
+ button_focused.xml
+ button_pressed.xml
+ button.xml

##b2: thêm style button vào style.xml

` <style name="button" parent="@android:style/Widget.Button">
            <item name="android:gravity">center_vertical|center_horizontal</item>
            <item name="android:textColor">#FFFFFFFF</item>
            <item name="android:shadowColor">#FF000000</item>
            <item name="android:shadowDx">0</item>
            <item name="android:shadowDy">-1</item>
            <item name="android:shadowRadius">0.2</item>
            <item name="android:textSize">16dip</item>
            <item name="android:textStyle">bold</item>
            <item name="android:background">@drawable/button</item>
            <item name="android:focusable">true</item>
            <item name="android:clickable">true</item>
        </style>`
        
##b3: thêm style vào button 
`style="@style/button"`

## một số thuộc tính thường dùng 
với
> pressed
`android:focusable="true"` </br>
> disabled 
` android:enabled="false"` </br>
###link app tham khảo
(![https://github.com/trantronghien/chat](https://cloud.githubusercontent.com/assets/13708331/16546087/e7cb164e-4169-11e6-8657-b17440b0f834.png))

<a href='http://naldzgraphics.net/tutorials/40-best-photoshop-tutorials-for-creating-buttons-and-badges/' target="_blank" > Custom Button Using Photoshop </a>


