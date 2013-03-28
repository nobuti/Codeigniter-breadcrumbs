Breadcrumbs is an small library that helps your manage HTML breadcrumbs with CodeIgniter.

## Instalation

* Put Breadcrumbs.php in application/library folder
* Put breadcrumbs.php in application/config folder

## Example of use

	// load Breadcrumbs
	$this->load->library('breadcrumbs');

	// add breadcrumbs
	$this->breadcrumbs->push('Section', '/section');
	  // $this->breadcrumbs->push('Section', site_url('section') );
	$this->breadcrumbs->push('Page', '/section/page');
	  // $this->breadcrumbs->push('Page', site_url('section/page') );

	// unshift crumb
	$this->breadcrumbs->unshift('Home', '/');
	  // $this->breadcrumbs->unshift('Home', site_url('') );

	// output
	$this->breadcrumbs->show();
