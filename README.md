Breadcrumbs is an small library that helps your manage HTML breadcrumbs with CodeIgniter.

## Instalation

* Put Breadcrumbs.php in application/library folder
* Put breadcrumbs.php in application/config folder

## Example of use

	// load Breadcrumbs
	$this->load->library('breadcrumbs');

	// add breadcrumbs
	$this->breadcrumbs->push('Section', '/section');
	$this->breadcrumbs->push('Page', '/section/page');

	// unshift crumb
	$this->breadcrumbs->unshift('Home', '/');

	// output
	$this->breadcrumbs->show();