History

 1826  asciinema rec
 1827* k get nodes
 1828* zsh
 1829* alias k=kubectl
 1830* k get nodes
 1831* k get svc
 1832* k get deploy
 1833* k get services -n projectcontour
 1834* k create deployment main --image=mirik12/k8sphp:latest
 1835* k create deployment web1 --image=mirik12/k8sphp:version1
 1836* k create deployment web2 --image=mirik12/k8sphp:version2
 1837* k create deployment webx --image=mirik12/k8sphp:versionx
 1838* k create deployment tomcat --image=tomcat:8.5.38
 1839* k get pods
 1840* history -n=20
 1841* k describe pods web1-647dd6fc5c-nx7mb
 1842* docker login
 1843* k create deployment main --image=mirik12/k8sphp:latest
 1844* k create deployment web1 --image=mirik12/k8sphp:version1
 1845* k get pods
 1846* docker version
 1847* > docker version\nClient:\n Cloud integration: v1.0.31\n Version:           20.10.24\n API version:       1.41\n Go version:        go1.19.7\n Git commit:        297e128\n Built:             Tue Apr  4 18:21:21 2023\n OS/Arch:           darwin/arm64\n Context:           default\n Experimental:      true\n\nServer: Docker Desktop 4.18.0 (104112)\n Engine:\n  Version:          20.10.24\n  API version:      1.41 (minimum version 1.12)\n  Go version:       go1.19.7\n  Git commit:       5d6db84\n  Built:            Tue Apr  4 18:17:07 2023\n  OS/Arch:          linux/arm64\n  Experimental:     false\n containerd:\n  Version:          1.6.18\n  GitCommit:        2456e983eb9e37e47538f59ea18f2043c9a73640\n runc:\n  Version:          1.1.4\n  GitCommit:        v1.1.4-0-g5fd4c4d\n docker-init:\n  Version:          0.19.0\n  GitCommit:        de40ad0
 1848* docker pull mirik12/k8sphp:version1
 1849* k create deployment web1 --image=mirik12mirik/k8sphp:version1
 1850* k delete 
 1851* kubectl delete deployment web1\n
 1852* k create deployment web1 --image=mirik12mirik/k8sphp:version1
 1853* k get pods
 1854* docker pull mirik12mirik/k8sphp:version1
 1855* docker pull
 1856* docker tag mirik12mirik/k8sphp:latest mirik12mirik/k8sphp:version1\n
 1857* docker push mirik12mirik/k8sphp:version1\n
 1858* kubectl create deployment web1 --image=mirik12mirik/k8sphp:version1\n
 1859* kubectl delete deployment web1\n
 1860* kubectl create deployment web1 --image=mirik12mirik/k8sphp:version1\n
 1861* k get pods
 1862* kubectl delete deployment web2\n
 1863* docker tag mirik12mirik/k8sphp:latest mirik12mirik/k8sphp:version2\n
 1864* docker push mirik12mirik/k8sphp:version2\n
 1865* kubectl create deployment web2 --image=mirik12mirik/k8sphp:version2
 1866* k get pods
 1867* kubectl delete deployment webx\n
 1868* docker tag mirik12mirik/k8sphp:latest mirik12mirik/k8sphp:versionx\n
 1869* docker push mirik12mirik/k8sphp:versionx\n
 1870* kubectl create deployment web2 --image=mirik12mirik/k8sphp:versionx
 1871* kubectl create deployment webx --image=mirik12mirik/k8sphp:versionx
 1872* k get pods
 1873* kubectl delete deployment main\n
 1874* docker tag mirik12mirik/k8sphp:latest mirik12mirik/k8sphp:main\n
 1875* docker push mirik12mirik/k8sphp:main\n
 1876* kubectl create deployment webx --image=mirik12mirik/k8sphp:main
 1877* kubectl create deployment main --image=mirik12mirik/k8sphp:main
 1878* k scale deployment main --replicas 2
 1879* k get deploy
 1880* k get svc
 1881* k expose deployment main --port=80
 1882* k expose deployment web1 --port=80
 1883* k expose deployment web2 --port=80
 1884* k expose deployment webx --port=80
 1885* k expose deployment tomcat --port=8080
 1886* k get svc
 1887* k get svc -o wide
 1888* cd kubernetes
 1889* cat ingress-hosts.yaml
 1890* cd ..
 1891* k get ingress
 1892* ll
 1893* cd kubernetes
 1894* k apply -f ingress-hosts.yaml
 1895* k get ingress
 1896* k describe ingress
 1897* k apply -f ingress-paths.yaml
 1898* k describe ingress-paths.yaml
 1899* k describe ingres
 1900* k describe ingress
 1901  history 50