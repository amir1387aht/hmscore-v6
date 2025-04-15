# hmscore-v6
An archive for hmscore sdk v6(2.2.0) used for liteWearable devices.

<b>How to use sdk:</b>
  1. Download the file in links.txt file
  2. Goto: C:\Users\%username%\AppData\Local\Huawei\Sdk
  3. Create a folder called "2.2.0" if doesn't exists already.
  4. Extract files inside zip file into that folder
  5. Enjoy

<b>How to change Deveco studio region:</b>
  1. Goto C:\Users\%username%\AppData\Roaming\Huawei\DevEcoStudio3.1\options
  2. Open country.region.xml with Notepad
  3. Find the line contains "<countryregion name="XX"/>"
  4. Set the name to "CN" (<countryregion name="CN"/>)
  5. Reload Deveco studio

<b>How to uploads app to liteWearable:</b>
  1. Build your app and copy the .hap file(Note that you should sign it, refer to huawei docs)
  2. Place your .hap file inside "haps" folder in your phone root folder(Create it if doesn't exists)
  3. Open Deveco assistant and tab Apps and click Install on your app name
  4. Wait to finish & Enjoy

<b>Links:</b>
  1. Huawei Docs: https://developer.huawei.com/consumer/en/doc/connectivity-Guides/dev-process-0000001051058039
