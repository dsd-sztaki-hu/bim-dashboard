# bim-dashboard

Setup

Eclipsben kell buildelni maven projektként.
A szerver indító \BIMserver\BimServerJar -> LocalDevBimServerStarter (Run as Java Application)

Program arguments:
-home "C:\{útvonal}\bim-dashboard\home"
-plugins "C:\{útvonal}\bim-dashboard\BIMserver-JavaScript-API"
-plugins "C:\{útvonal}\bim-dashboard\BIMsurfer-before2019"
-plugins "C:\{útvonal}\bim-dashboard\bimvie.ws"
-plugins "C:\{útvonal}\bim-dashboard\BinarySerializers\BinarySerializers"
-plugins "C:\{útvonal}\bim-dashboard\console\Console"
-plugins "C:\{útvonal}\bim-dashboard\GltfSerializers\Gltf"
-plugins "C:\{útvonal}\bim-dashboard\IfcOpenShell-BIMserver-plugin"
-plugins "C:\{útvonal}\bim-dashboard\IfcPlugins\IfcPlugins"

VM arguments:
-Xmx4g

Belépés:
Username: admin@bimserver.org
Password: admin
