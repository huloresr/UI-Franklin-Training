SASS
    - dont use {} and ;
SCSS
    use {} amd ;


Installation required for using SASS / SCSS 
sass has its own compiler

node in a pre-requisite
    npm init
    npm install -g sass


    basic structure :
        resources / scss
            global.scss
            layout.scss
            style.scss
            typography.scss
            variables.scss
        resources / components
            component.scss
            header.scss
            footer.scss
            
			
	scripts : {
		build : sass --watch resources/scss:resources/style
	}
	
