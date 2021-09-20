# laravel-package-creator-docker
This is a docker laravel setup that can be used for package development
Follow the following steps to setup a laravel package development environment
<ul>
<li>Clone or fork repository</li>
<li>Go to https://github.com/spatie/package-skeleton-laravel to create a package template</li>
<li>create a directory called packages</li>
<li>clone the package directory generated from spatie repository into the packages folder </li>
<li>goto the root directory of the project on your terminal and run the following command</li>
  <ul>
  <li> docker-compose up -d</li>
  <li> docker exec -it pkg_creator_app bash</li>
  </ul>
<li>Navigate to the package folder in the packages directory</li>
<li>Run this command php ./configure.php</li>
</ul>
