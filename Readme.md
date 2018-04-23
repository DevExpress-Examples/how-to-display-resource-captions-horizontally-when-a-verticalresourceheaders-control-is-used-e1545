# How to display resource captions horizontally when a VerticalResourceHeaders control is used


<p>This example employs the <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraSchedulerReportingHorizontalWeektopic">ResourceInfo</a> controls and handles its <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraSchedulerReportingTextInfoControlBase_CustomizeTexttopic"> CustomizeText event</a> to display the resource captions instead of the VerticalResourceHeaders control so that the text is horizontal.<br />
Starting from the v2009 vol.2 release the CustomDrawResourceHeader event enables you to draw the caption horizontally.</p>


<h3>Description</h3>

<p>This example uses the <strong>CustomDrawResourceHeader</strong> event to draw the horizontal caption manually via the <a href="http://documentation.devexpress.com/#CoreLibraries/DevExpressUtilsDrawingGraphicsCache_DrawStringtopic">GraphicsCache.DrawString</a> method.</p>

<br/>


