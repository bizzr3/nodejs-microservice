docker run -it ubuntu --name="acdr-generator"
docker run -itdv ~/projects/nodejs/soket/performance:/application --name="nana-kpi" -p 22100:80 acdr-generator ./bin/bash 
