<b>RESUMO:</b><br>Configuração do CloudWatch em Ubuntu 18.04 para coleta de estatística.

<b>Vídeo da implementação: https://www.youtube.com/watch</b>

------------------------------------------------------------------------------

<b>1- </b>Atachar a politica: (CloudWatchMonitoring.json do repositório) na instância que deseja coletar:

------------------------------------------------------------------------------

<b>2-</b> Executar as seguintes linhas no terminal: (usar install_saopaulo.sh se estiver em SP)

cd /tmp<br>
sudo wget https://raw.githubusercontent.com/aldeiacloud/cloudwatch_ubuntu18/main/install_virginia.sh<br>
sudo chmod +x install.sh<br>
sudo ./install.sh<br>

------------------------------------------------------------------------------

<b>3-</b> Aguardar 1 minuto e agora podera criar o Dashboard para visualização.
