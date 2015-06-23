# cakephp-image-component 
this is an Image Component for CakePHP 3
i just make a component for CakePHP, original script is on http://code.tutsplus.com/tutorials/image-resizing-made-easy-with-php--net-10362
the main function of this component is to resize an image

## Usage 
Load image
$this->loadComponent('Image');

Open an Image
$this->Image->OpenImage($filePath);

Resize Image
$this->Image->resizeImage(50,50);

Save Image
$this->Image->saveImage(WWW_ROOT . 'test.png');
