create vm easily using bash
  az vm create \
    --resource-group 1-ef9323f4-playground-sandbox \
    --name myVM-1 \
    --size standard_d2s_v3 \
    --image win2022datacenter \
    --admin-username azure \
    --admin-password @R.cloud.temp@123 \
    --no-wait
