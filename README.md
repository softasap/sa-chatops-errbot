sa-chatops-errbot
=================

[![Build Status](https://travis-ci.org/softasap/sa-chatops-errbot.svg?branch=master)](https://travis-ci.org/softasap/sa-chatops-errbot)


Example of usage:

Simple

```YAML

     - {
         role: "sa-chatops-errbot"
       }


```

Advanced

```YAML

nginx_conf_properties:

     - {
         role: "sa-chatops-errbot"
       }


```



Usage with ansible galaxy workflow
----------------------------------

If you installed the `sa-chatops-errbot` role using the command


`
   ansible-galaxy install softasap.sa-chatops-errbot
`

the role will be available in the folder `library/softasap.sa-chatops-errbot`
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-chatops-errbot"
       }

```




Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html 
