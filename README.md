# CodeIgniter-Breadcrumbs

Breadcrumbs is an small library that helps your manage HTML breadcrumbs with CodeIgniter.



## Example

// load libary
$this->load->library('breadcrumb');

// add breadcrumbs
$this->breadcrumb->add('Home', '/');
$this->breadcrumb->add('Page', '/page');

// output
$this->breadcrumb->show();