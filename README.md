# quick-assets-with-npm
Start building for WordPress in seconds with @wordpress/scripts
- can start building normal JS/SCSS 
- can start building wp.blocks 

    ```wp.blocks.registerBlockType('apsolut/ap-quick-assets',{
    title: 'AP Quick Assets',
    icon: 'smiley',
    category: 'common',  // layout, typography
    attributes: {
        yourColor: {type: 'string'},
    },
    edit: function (props) {
       
    },
    save: function(props) {
        // dont need to use this
        return null
    },

    })


    // install
    npm install

    // start and build
    npm run start
    npm run build


