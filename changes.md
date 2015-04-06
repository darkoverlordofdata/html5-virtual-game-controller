

		// Handle case when target is a string or something( possible in deep copy )
		//if( typeof target !== "object" && !typeof target === 'function' )
        // invalid operator precedence should be:
        if( typeof target !== "object" && typeof target !== 'function' )


			// Don't do anything if there's no touch support
			//if( ! 'ontouchstart' in document.documentElement )
			//	return;
            // invalid operator precedence should be:
            if (!('ontouchstart' in document.documentElement)) return;


            this.ready = true;
			//window.requestAnimationFrame( this.renderWrapper );
