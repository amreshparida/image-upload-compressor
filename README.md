# image-upload-compressor

# Usage : 
Step 1: Include this script in your page head tag as 

    <script src="https://cdn.jsdelivr.net/gh/amreshparida/image-upload-compressor/imc.min.js"></script>
 
Step 2: Call the function ImageUploadCompressor('your-input-file-image-classname') on page load as

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            let x = new ImageUploadCompressor('my-image-field');
        });
    </script>
