### EPiwikAnalyticsWidget

#### About
EPiwikAnalyticsWidget is a Yii Widget that allows site administrators to quickly place a Piwik Analytics code onto their site by only configuring a single line of code.

#### Usage

~~~
[PHP]
    <?php $this->widget('ext.analytics.EPiwikAnalyticsWidget', array('id'=>$site_id, 'baseUrl'=>$baseUrl)); ?>
~~~
#### Params
The widget requires 2 parameters: the Piwik site id and the url of the piwik server

The variable declarations are as follows:

    @var int id     	The Piwik site id found in the piwik site admin panel
    @var url baseUrl	The base url of the piwik server. Should be a full url beginning with http[s]://.

If either parameters are missing, the extension will throw a CException describing the error.


#### Resources

EPiwikAnalytics is available on GitHub

 * [Fork on Github](https://github.com/charlesportwoodii/EPiwikAnalyticsWidget)