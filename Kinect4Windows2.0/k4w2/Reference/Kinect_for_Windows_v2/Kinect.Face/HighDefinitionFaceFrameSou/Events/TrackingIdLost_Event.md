HighDefinitionFaceFrameSource.TrackingIdLost Event  
==================================================  

Occurs when the tracking ID is lost.<span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public:  
event TypedEventHandler&lt;<a href="../../HighDefinitionFaceFrameSou.md">HighDefinitionFaceFrameSource</a>, <a href="../../TrackingIdLostEventArgs.md">TrackingIdLostEventArgs</a>, &gt;^ TrackingIdLost {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../HighDefinitionFaceFrameSou.md">HighDefinitionFaceFrameSource</a>, <a href="../../TrackingIdLostEventArgs.md">TrackingIdLostEventArgs</a>, &gt;^ value);  
         void remove (EventRegistrationToken token);  
}</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../HighDefinitionFaceFrameSou.md">HighDefinitionFaceFrameSource</a>, <a href="../../TrackingIdLostEventArgs.md">TrackingIdLostEventArgs</a>, &gt; TrackingIdLost</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>function onTrackingIdLost(eventArgs) { /* Your code */ }  

// addEventListener syntax  
highDefinitionFaceFrameSource.addEventListener(&quot;trackingidlost&quot;, onTrackingIdLost);  
highDefinitionFaceFrameSource.removeEventListener(&quot;trackingidlost&quot;, onTrackingIdLost);  

- or -  

highDefinitionFaceFrameSource.ontrackingidlost = onTrackingIdLost;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EDB"></span>

See also  
========  

<span id="ID4EFB"></span>
#### Reference  

[HighDefinitionFaceFrameSource Class](../../HighDefinitionFaceFrameSou.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : TrackingIdLost Event
RLTitle : HighDefinitionFaceFrameSource.TrackingIdLost Event
KeywordK : TrackingIdLost event
KeywordK : HighDefinitionFaceFrameSource.TrackingIdLost event
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.TrackingIdLost
KeywordF : HighDefinitionFaceFrameSource.TrackingIdLost
KeywordF : TrackingIdLost
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.TrackingIdLost
KeywordA : E:Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.TrackingIdLost
AssetID : E:Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.TrackingIdLost
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.TrackingIdLost
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
