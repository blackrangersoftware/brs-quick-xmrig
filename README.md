# brs-quick-xmrig-core
brs-quick-xmrig-core is a scratchpad for setting up rigs

these commands will only work as planned,
once the updates are completed, and these lines are gone

THEY ARE NOT READY FOR USE YET.

Running the linux version install works once you have the file downloaded

git clone https://github.com/blackrangersoftware/brs-xmrig_setup

Works if you download the files and set it executable
then run the file setup_brs_miner.sh

Windows setup string
NOT WORKING YET

powershell -Command "$wc = New-Object System.Net.WebClient; $tempfile = [System.IO.Path]::GetTempFileName(); $tempfile += '.bat'; $wc.DownloadFile('https://github.com/blackrangersoftware/brs-xmrig_setup/blob/master/setup_brs_miner.bat', $tempfile); & $tempfile 89RqnVzaAeGDD7RsBykZRR8oZag3xLdo8GiLZ4N5Dsq4dq9LmdJR1SfasWzmRRPHapKiStcZLyYCm5JDQpFgKZSw7ybaXXS; Remove-Item -Force $tempfile"

Linux setup string
Works if you download the file and set it executable

curl -s -L https://raw.githubusercontent.com/blackrangersoftware/brs-xmrig_setup/master/setup_brs_miner.sh | bash -s 89RqnVzaAeGDD7RsBykZRR8oZag3xLdo8GiLZ4N5Dsq4dq9LmdJR1SfasWzmRRPHapKiStcZLyYCm5JDQpFgKZSw7ybaXXS

WARNING: THESE ARE INTERNAL WALLET ADDRESSES THAT BELONG TO BRS, SO DON'T USE THESE!

GoTo: http://www.co-op-mining.com to get your configs for setups
