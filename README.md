# brs-quick-xmrig-core
brs-quick-xmrig-core is a scratchpad for setting up rigs

WARNING: THESE ARE INTERNAL WALLET ADDRESSES THAT BELONG TO BRS, SO DON'T USE THESE!

GoTo: http://www.co-op-mining.com to get your configs for setups

Windows setup string

powershell -Command "$wc = New-Object System.Net.WebClient; $tempfile = [System.IO.Path]::GetTempFileName(); $tempfile += '.bat'; $wc.DownloadFile('https://raw.githubusercontent.com/blackrangersoftware/brs-xmrig_setup/master/setup_brs_miner.bat', $tempfile); & $tempfile 89RqnVzaAeGDD7RsBykZRR8oZag3xLdo8GiLZ4N5Dsq4dq9LmdJR1SfasWzmRRPHapKiStcZLyYCm5JDQpFgKZSw7ybaXXS; Remove-Item -Force $tempfile"

Linux setup/install command string

curl -s -L https://raw.githubusercontent.com/blackrangersoftware/brs-xmrig_setup/master/setup_brs_miner.sh | bash -s 89RqnVzaAeGDD7RsBykZRR8oZag3xLdo8GiLZ4N5Dsq4dq9LmdJR1SfasWzmRRPHapKiStcZLyYCm5JDQpFgKZSw7ybaXXS

Linux uninstall command string

curl -s -L https://raw.githubusercontent.com/blackrangersoftware/brs-xmrig_setup/master/uninstall_brs_miner.sh | bash -s

