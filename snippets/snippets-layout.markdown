##Layout

**Basic App Layout with Navbar:**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no, width=device-width">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="apple-touch-startup-image" href="startup.png">
        <link rel="apple-touch-icon" href="app-icon.png"/>
        <link rel="shortcut icon" href="favicon.ico">
        <title>Title</title>
        <link rel="stylesheet" href="chui.css">
        <style type="text/css">
            /* Local Styles Here */
            
        </style>
        <script src="chocolatechip.js" type="text/javascript"></script>
        <script src="chui.js" type="text/javascript"></script>
        <script type="text/javascript">
            /* Local JavaScript Here */
            $.ready(function() {
                
            });
            
        </script>
    </head>
    <body>
        <app>
            <view id="main" ui-background-style="striped" ui-navigation-status="current">
                <navbar>
                    <h1>Title</h1>
                </navbar>
                <subview id="subview_01" ui-associations="withNavBar">
                    <scrollpanel>
                    
                    </scrollpanel>
                </subview>
            </view>
        </app>
    </body>
    </html>


**Basic App Layout with Navbar and Bottom Toolbar:**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no, width=device-width">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="apple-touch-startup-image" href="startup.png">
        <link rel="apple-touch-icon" href="app-icon.png"/>
        <link rel="shortcut icon" href="favicon.ico">
        <title>Title</title>
        <link rel="stylesheet" href="chui.css">
        <style type="text/css">
            /* Local Styles Here */
            
        </style>
        <script src="chocolatechip.js" type="text/javascript"></script>
        <script src="chui.js" type="text/javascript"></script>
        <script type="text/javascript">
            /* Local JavaScript Here */
            $.ready(function() {
                
            });
            
        </script>
    </head>
    <body>
        <app>
            <view id="main" ui-background-style="striped" ui-navigation-status="current">
                <navbar>
                    <h1>Title</h1>
                </navbar>
                <subview id="subview_01" ui-associations="withNavBar withBottomToolBar">
                    <scrollpanel>
                    
                    </scrollpanel>
                </subview>
                <toolbar ui-placement="bottom">
                </toolbar>
            </view>
        </app>
    </body>
    </html>


**Basic App Layout with Bottom Toolbar:**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no, width=device-width">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="apple-touch-startup-image" href="startup.png">
        <link rel="apple-touch-icon" href="app-icon.png"/>
        <link rel="shortcut icon" href="favicon.ico">
        <title>Title</title>
        <link rel="stylesheet" href="chui.css">
        <style type="text/css">
            /* Local Styles Here */
            
        </style>
        <script src="chocolatechip.js" type="text/javascript"></script>
        <script src="chui.js" type="text/javascript"></script>
        <script type="text/javascript">
            /* Local JavaScript Here */
            $.ready(function() {
                
            });
            
        </script>
    </head>
    <body>
        <app>
            <view id="main" ui-background-style="striped" ui-navigation-status="current">
                <subview id="subview_01" ui-associations="withBottomToolBar">
                    <scrollpanel>
                    
                    </scrollpanel>
                </subview>
                <toolbar ui-placement="bottom">
                </toolbar>
            </view>
        </app>
    </body>
    </html>


**Basic App Layout with Top Toolbar**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no, width=device-width">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="apple-touch-startup-image" href="startup.png">
        <link rel="apple-touch-icon" href="app-icon.png"/>
        <link rel="shortcut icon" href="favicon.ico">
        <title>Title</title>
        <link rel="stylesheet" href="chui.css">
        <style type="text/css">
            /* Local Styles Here */
            
        </style>
        <script src="chocolatechip.js" type="text/javascript"></script>
        <script src="chui.js" type="text/javascript"></script>
        <script type="text/javascript">
            /* Local JavaScript Here */
            $.ready(function() {
                
            });
            
        </script>
    </head>
    <body>
        <app>
            <view id="main" ui-background-style="striped" ui-navigation-status="current">
                <toolbar>
                </toolbar>
                <subview id="subview_01" ui-associations="withTopToolBar">
                    <scrollpanel>
                    
                    </scrollpanel>
                </subview>
            </view>
        </app>
    </body>
    </html>


**Basic App Layout with Top Toolbar and Bottom Toolbar:**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no, width=device-width">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="apple-touch-startup-image" href="startup.png">
        <link rel="apple-touch-icon" href="app-icon.png"/>
        <link rel="shortcut icon" href="favicon.ico">
        <title>Title</title>
        <link rel="stylesheet" href="chui.css">
        <style type="text/css">
            /* Local Styles Here */
            
        </style>
        <script src="chocolatechip.js" type="text/javascript"></script>
        <script src="chui.js" type="text/javascript"></script>
        <script type="text/javascript">
            /* Local JavaScript Here */
            $.ready(function() {
                
            });
            
        </script>
    </head>
    <body>
        <app>
            <view id="main" ui-background-style="striped" ui-navigation-status="current">
                <toolbar>
                </toolbar>
                <subview id="subview_01" ui-associations="withTopBar withBottomToolBar">
                    <scrollpanel>
                    
                    </scrollpanel>
                </subview>
                <toolbar ui-placement="bottom">
                </toolbar>
            </view>
        </app>
    </body>
    </html>


**Basic App Layout with No Navbar or Toolbar:**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no, width=device-width">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="apple-touch-startup-image" href="startup.png">
        <link rel="apple-touch-icon" href="app-icon.png"/>
        <link rel="shortcut icon" href="favicon.ico">
        <title>Title</title>
        <link rel="stylesheet" href="chui.css">
        <style type="text/css">
            /* Local Styles Here */
            
        </style>
        <script src="chocolatechip.js" type="text/javascript"></script>
        <script src="chui.js" type="text/javascript"></script>
        <script type="text/javascript">
            /* Local JavaScript Here */
            $.ready(function() {
                
            });
            
        </script>
    </head>
    <body>
        <app>
            <view id="main" ui-background-style="striped" ui-navigation-status="current">
                <subview id="subview_01">
                    <scrollpanel>
                    
                    </scrollpanel>
                </subview>
            </view>
        </app>
    </body>
    </html>


**Basic Navigation List (Two Levels):**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no, width=device-width">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="apple-touch-startup-image" href="startup.png">
        <link rel="apple-touch-icon" href="app-icon.png"/>
        <link rel="shortcut icon" href="favicon.ico">
        <title>Title</title>
        <link rel="stylesheet" href="chui.css">
        <style type="text/css">
            /* Local Styles Here */
            
        </style>
        <script src="chocolatechip.js" type="text/javascript"></script>
        <script src="chui.js" type="text/javascript"></script>
        <script type="text/javascript">
            /* Local JavaScript Here */
            $.ready(function() {
                
            });
            
        </script>
    </head>
    <body>
        <app>
            <view id="main" ui-background-style="striped" ui-navigation-status="current">
                <navbar>
                    <h1>Title</h1>
                </navbar>
                <subview id="subview_01" ui-associations="withNavBar">
                    <scrollpanel>
                        <tableview>
                            <tablecell href="#item_01_view" ui-implements="disclosure">
                                <celltitle>Item</celltitle>
                            </tablecell>
                        </tableview>
                    </scrollpanel>
                </subview>
            </view>
            <view id="item_01_view" ui-navigation-status="upcoming" ui-background-style="slanted-right">
                <navbar>
                    <uibutton ui-implements="back">
                        <label>Back</label>
                    </uibutton>
                    <h1>Title</h1>
                </navbar>
                <subview id="subview_01" ui-associations="withNavBar">
                    <scrollpanel>
                        <tableview ui-tablecell-order="stacked">
                            <tablecell href="#item_01_detail_view">
                                <cellcounter>1</cellcounter>
                                <celltitle>Item</celltitle>
                                <cellsubtitle>Item Subtitle</cellsubtitle>
                            </tablecell>
                        </tableview>
                    </scrollpanel>
                </subview>
            </view>
        </app>
    </body>
    </html>


**Basic Navigation List (Three Levels):**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no, width=device-width">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="apple-touch-startup-image" href="startup.png">
        <link rel="apple-touch-icon" href="app-icon.png"/>
        <link rel="shortcut icon" href="favicon.ico">
        <title>Title</title>
        <link rel="stylesheet" href="chui.css">
        <style type="text/css">
            /* Local Styles Here */
            
        </style>
        <script src="chocolatechip.js" type="text/javascript"></script>
        <script src="chui.js" type="text/javascript"></script>
        <script type="text/javascript">
            /* Local JavaScript Here */
            $.ready(function() {
                
            });
            
        </script>
    </head>
    <body>
        <app>
            <view id="main" ui-background-style="striped" ui-navigation-status="current">
                <navbar>
                    <h1>Title</h1>
                </navbar>
                <subview id="subview_01" ui-associations="withNavBar">
                    <scrollpanel>
                        <tableview>
                            <tablecell href="#item_01_view" ui-implements="disclosure">
                                <celltitle>Item</celltitle>
                            </tablecell>
                        </tableview>
                    </scrollpanel>
                </subview>
            </view>
            <view id="item_01_view" ui-navigation-status="upcoming" ui-background-style="slanted-right">
                <navbar>
                    <uibutton ui-implements="back">
                        <label>Back</label>
                    </uibutton>
                    <h1>Title</h1>
                </navbar>
                <subview id="subview_01" ui-associations="withNavBar">
                    <scrollpanel>
                        <tableview ui-tablecell-order="stacked">
                            <tablecell href="#item_01_detail_view" ui-implements="detail-disclosure">
                                <cellcounter>1</cellcounter>
                                <celltitle>Item</celltitle>
                                <cellsubtitle>Item Subtitle</cellsubtitle>
                            </tablecell>
                        </tableview>
                    </scrollpanel>
                </subview>
            </view>
            <view id="item_01_detail_view" ui-navigation-status="upcoming" ui-background-style="squared">
                <navbar>
                    <uibutton ui-implements="back">
                        <label>Back</label>
                    </uibutton>
                    <h1>Title</h1>
                </navbar>
                <subview id="subview_01" ui-associations="withNavBar">
                    <scrollpanel>
                        <tableview ui-tablecell-order="stacked">
                            <tablecell class="ui-no-hover">
                                <celltitle>Item</celltitle>
                                <cellsubtitle>Item Subtitle</cellsubtitle>
                                <celldetail>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                                </celldetail>
                            </tablecell>
                        </tableview>
                    </scrollpanel>
                </subview>
            </view>
        </app>
    </body>
    </html>


**Current View with Navbar and Subview:**

    <view id="main">
        <navbar>
            <h1>Title</h1>
        </navbar>
        <subview ui-associations="withNavBar">
            <scrollpanel>
            
            </scrollpanel>
        </subview>
    </view>



**Upcoming View with "Back" Navbar and Subview:**

    <view id="view_02" ui-navigation-status="upcoming">
        <navbar>
            <uibutton ui-implements="back">
                <label>Back</label>
            </uibutton>
            <h1>Title</h1>
        </navbar>
        <subview ui-associations="withNavBar">
            <scrollpanel>
            
            </scrollpanel>
        </subview>
    </view>



**Upcoming View with "Back" Navbar, Bottom Toolbar and Subview**

    <view id="view_02" ui-navigation-status="upcoming">
        <navbar>
            <uibutton ui-implements="back">
                <label>Back</label>
            </uibutton>
            <h1>Title</h1>
        </navbar>
        <subview ui-associations="withNavBar withBottomToolbar">
            <scrollpanel>
            
            </scrollpanel>
        </subview>
        <toolbar ui-placement="bottom">
        
        </toolbar>
    </view>