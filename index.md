
*Cloud Browser* is available on *Microsoft Store* and *Google Play Store*. 

The app allows:
* easy management of multiple cloud storage accounts
* playing media files directly from cloud

Currently it supports browsing through the following cloud storage-like services:

<ul class="cloud-list">
  <style>
    .cloud-list img {
      vertical-align: middle;
      margin: 10px;
      max-height: 50px;
      max-width: 50px;
    }
    .cloud-list li {
      display: inline-block;
    }
  </style>
  <li><img src="./image/google.png" />Google Drive</li>
  <li><img src="./image/dropbox.png" />Dropbox</li>
  <li><img src="./image/onedrive.png" />OneDrive</li>
  <li><img src="./image/box.png" />Box</li>
  <li><img src="./image/pcloud.png" />pCloud</li>
  <li><img src="./image/hubic.png" />hubiC</li>
  <li><img src="./image/mega.png" />MEGA</li>
  <li><img src="./image/yandex.png" />Yandex.Disk</li>
  <li><img src="./image/amazons3.png" />AmazonS3</li>
  <li><img src="./image/webdav.png" />WebDAV</li>
  <li><img src="./image/gphotos.png" />Google Photos</li>
  <li><img src="./image/local.png" />Local drive</li>
</ul>

All versions of the app are built on top of open source 
[`libcloudstorage`](https://github.com/lemourin/libcloudstorage) library.
If you need new cloud storage services added, you are strongly encouraged to 
implement them in [`libcloudstorage`](https://github.com/lemourin/libcloudstorage).