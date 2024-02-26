# Flex Element Upload

**Flex Element Upload** is a simple and useful npm package that helps you upload files in your projects. It utilizes axios for file upload functionality by simply specifying the upload URL (for example /upload.php). You can set limits for file types, dimensions, and size. It displays information about selected files and allows you to set a limit for the number of uploads. Additionally, it can preview images on the first page load.

## Building Features

### API (POST)

If you set `api -> ssr:true`, it will wait for a URL to handle file uploads in the background. Here's an example of how to configure it:

```javascript   
 api={{
    ssr: true,
    url: "http://localhost/upload.php",
 }}
