golab app overview

var views = {
    ‘dashboard’ : ‘here we have some views with app and samples stats’,
    ‘samples’ : {
        grid : ‘list with the samples’,
        workflow : ‘board with the samples’
    },
    ‘patients’ : ‘list with the patients’,
    ‘administration’ : {
        ‘methods’ : ‘here we add methods that can be applied to tests’,
        ‘templates’ : ‘here we have the results template for each test that is send to the patient’,
        ‘tests’ : ‘analytical procedure that is performed on samples’,
        ‘users’ : ‘here we can create, delete or edit current users’
    },
    ‘settings’ : {
        ‘restoreData’ : ‘reset values to default in the golab app so it always work’
        ‘edit’ : ‘default reviewer and default notifications email, where notifications are send in demo app’
    };
};
var users = {
    ‘type’ : [‘admin’, ‘technicians’, ‘developers’]
};
var samples = {
    ‘status’ : [‘new’, ‘processing’, ‘in review’, ‘ready’, ‘with issues’, ‘rejected’, ‘discarded’]
}

Features
Report generate
Notifications: created, ready, rejected, expired and about to expire
Landing 
Mobile app

Stack
Slingr
Webflow
FlutterFlow
