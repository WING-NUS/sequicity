# Sequicity

- training with default parameters

> python model.py -mode train -model [tsdf-camrest|tsdf-kvret]

(optional: configuring with cmdline)

> python model.py -mode train -model [tsdf-camrest|tsdf-kvret] -config lr=0.003 batch_size=32

- testing

> python model.py -mode test -model [tsdf-camrest|tsdf-kvret]

- reinforcement fine-tuning

> python model.py -mode train -mode [tsdf-camrest|tsdf-kvret] -config lr=0.0001