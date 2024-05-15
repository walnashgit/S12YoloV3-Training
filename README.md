# S12YoloV3-Training

### Trainig logs for YoloV3 model trained on custom dataset.

For details on model and dataset used see this [repo](https://github.com/walnashgit/S12YoloV3CustomDataSet)

## Logs:

Namespace(epochs=280, batch_size=10, accumulate=4, cfg='cfg/yolov3-custom.cfg', data='data/customdata/custom.data', multi_scale=False, img_size=[512], rect=False, resume=False, nosave=True, notest=False, evolve=False, bucket='', cache_images=True, weights='weights/yolov3-spp-ultralytics.pt', name='', device='', adam=False, single_cls=False)
Using CUDA device0 _CudaDeviceProperties(name='Tesla T4', total_memory=15102MB)

Run 'tensorboard --logdir=runs' to view tensorboard at http://localhost:6006/
WARNING: smart bias initialization failure.
WARNING: smart bias initialization failure.
WARNING: smart bias initialization failure.
Model Summary: 225 layers, 6.25733e+07 parameters, 6.25733e+07 gradients
Image sizes 512 - 512 train, 512 test
Using 2 dataloader workers
Starting training for 280 epochs...

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190  0.000676   0.00526  0.000654    0.0012

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190         0         0   0.00127         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190         0         0   0.00759         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190         0         0    0.0439         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190         1   0.00526     0.297    0.0105

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190         1   0.00526     0.619    0.0105

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.741     0.286     0.563     0.413

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.546     0.759     0.688     0.635

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.205     0.895     0.568     0.334

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.199     0.905     0.694     0.326

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.29     0.926     0.581     0.442

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.547     0.878      0.71     0.674

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.376     0.942     0.669     0.537

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.32     0.953     0.769     0.479

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.315     0.952     0.759     0.474

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.285     0.953     0.732     0.439

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.375     0.953     0.641     0.538

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.231     0.963     0.295     0.373

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.353     0.963     0.492     0.516

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.592     0.958     0.881     0.731

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.594     0.926     0.739     0.724

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.563     0.953      0.82     0.708

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.529     0.958     0.741     0.682

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.584     0.968     0.888     0.729

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.653     0.963     0.839     0.779

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.911     0.963     0.978     0.936

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.714     0.932     0.888     0.808

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.578     0.937     0.696     0.715

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.811     0.905     0.914     0.855

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.851     0.933     0.945      0.89

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.973     0.895     0.987     0.932

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.744       0.9     0.867     0.814

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.848     0.842     0.897     0.845

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.663     0.974     0.843     0.789

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.675     0.953     0.837      0.79

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.851     0.974     0.939     0.908

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.717     0.979     0.834     0.827

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.584     0.979     0.798     0.732

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.916     0.914     0.972     0.915

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.825     0.958     0.972     0.886

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.93     0.953     0.984     0.941

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.744     0.942      0.87     0.831

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.682     0.963     0.925     0.799

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.756      0.98     0.967     0.854

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.804     0.979     0.952     0.883

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size

Model Bias Summary:    layer        regression        objectness    classification
                          89      -0.13+/-0.21      -9.04+/-1.55       0.02+/-0.01 
                         101       0.09+/-0.21      -9.74+/-0.93       0.04+/-0.00 
                         113       0.17+/-0.22      -9.08+/-1.61      -0.00+/-0.01 
                 all       101       190     0.814     0.968     0.968     0.884

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.782     0.974     0.935     0.867

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.93     0.989     0.983     0.959

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.762     0.989     0.923     0.861

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.892     0.995     0.979      0.94

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.948         1     0.987     0.973

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.931     0.998      0.99     0.964

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.935         1      0.99     0.966

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.961     0.995     0.991     0.978

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.851     0.979      0.93      0.91

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.941     0.989     0.992     0.965

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.896     0.989      0.97      0.94

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.813     0.984     0.945      0.89

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.875     0.984     0.967     0.926

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.894     0.995      0.98     0.942

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.877     0.984     0.968     0.927

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.868     0.989     0.978     0.925

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.846     0.984     0.931      0.91

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.895     0.979     0.956     0.935

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.862     0.984     0.977     0.919

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.939     0.977     0.988     0.958

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.917     0.984     0.972     0.949

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.963     0.989     0.994     0.976

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.906     0.995     0.992     0.948

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.901     0.979     0.981     0.938

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.938     0.984     0.986     0.961

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.872     0.989     0.983     0.927

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.937     0.995     0.987     0.965

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.957     0.984     0.987      0.97

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.969     0.976     0.988     0.972

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.969     0.979      0.99     0.974

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.968     0.974      0.99     0.971

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.963     0.968     0.989     0.966

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.97     0.984     0.991     0.977

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.965     0.984     0.991     0.974

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.963     0.989     0.993     0.976

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.963     0.995     0.994     0.979

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.977         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.978         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.97         1     0.994     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.97         1     0.993     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.96         1     0.994     0.979

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.969         1     0.994     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.957         1     0.994     0.978

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.964     0.999     0.994     0.982

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.968         1     0.993     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.964         1     0.994     0.982

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.962         1     0.994     0.981

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.967     0.995     0.995     0.981

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.972         1     0.995     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.976         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.971         1     0.994     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.982         1     0.994     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.983         1     0.995     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987         1     0.995     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.986         1     0.995     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.986         1     0.995     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.983         1     0.995     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.979         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.981         1     0.995      0.99

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.977         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.97         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.968         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.971         1     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.973         1     0.995     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.976         1     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.977         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.984     0.998     0.995     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.992         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.988         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99         1     0.994     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.981         1     0.994      0.99

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.975         1     0.993     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.977         1     0.994     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.988         1     0.994     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.984         1     0.994     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.984         1     0.994     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.986         1     0.994     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.985         1     0.994     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.985         1     0.994     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987         1     0.994     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.984     0.999     0.995     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.984     0.999     0.995     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.983         1     0.995     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.974     0.998     0.995     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.971     0.995     0.994     0.983

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.971     0.995     0.995     0.983

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.976     0.989     0.994     0.983

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.979     0.989     0.994     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.979     0.995     0.994     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.977     0.995     0.994     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.984     0.994     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.964     0.991      0.99     0.978

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.982     0.989     0.995     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.983     0.989     0.994     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.985     0.989     0.995     0.987

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.979     0.991     0.995     0.985

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.982     0.995     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.984     0.999     0.995     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.98         1     0.994      0.99

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.968         1     0.994     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.973         1     0.994     0.986

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.976         1     0.994     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.977         1     0.994     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.979         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.983         1     0.995     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.983         1     0.995     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.984         1     0.995     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.978         1     0.995     0.989

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.969         1     0.995     0.984

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.979     0.997     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.986     0.995     0.995      0.99

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989     0.995     0.995     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.986     0.995     0.995      0.99

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99     0.995     0.995     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991     0.995     0.995     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99     0.995     0.995     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.995     0.998     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.995     0.999     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.994         1     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.992         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.995     0.999     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.995     0.999     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991     0.995     0.995     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99     0.995     0.995     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991     0.995     0.995     0.993

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99     0.995     0.995     0.992

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99     0.999     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99         1     0.994     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99     0.999     0.994     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.988         1     0.994     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.984     0.998     0.993     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987     0.995     0.994     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987     0.995     0.995     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987     0.995     0.995     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987     0.995     0.995     0.991

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.982     0.995     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.985     0.995     0.995      0.99

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.981     0.995     0.995     0.988

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.992         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.992         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.993         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.994         1     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.994         1     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.994         1     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.995     0.999     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.995         1     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.994         1     0.995     0.997

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.993         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.993         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.993         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.988         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.988         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.987         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.988         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.988         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.989         1     0.995     0.994

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190      0.99         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.995

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
                 all       101       190     0.991         1     0.995     0.996
280 epochs completed in 0.841 hours.

2024-05-09 19:11:07.685476: E external/local_xla/xla/stream_executor/cuda/cuda_dnn.cc:9261] Unable to register cuDNN factory: Attempting to register factory for plugin cuDNN when one has already been registered
2024-05-09 19:11:07.685532: E external/local_xla/xla/stream_executor/cuda/cuda_fft.cc:607] Unable to register cuFFT factory: Attempting to register factory for plugin cuFFT when one has already been registered
2024-05-09 19:11:07.686947: E external/local_xla/xla/stream_executor/cuda/cuda_blas.cc:1515] Unable to register cuBLAS factory: Attempting to register factory for plugin cuBLAS when one has already been registered
2024-05-09 19:11:08.826402: W tensorflow/compiler/tf2tensorrt/utils/py_utils.cc:38] TF-TRT Warning: Could not find TensorRT
Caching labels (101 found, 0 missing, 0 empty, 0 duplicate, for 101 images): 100%|██████████| 101/101 [00:00<00:00, 402.75it/s]
Caching images (0.1GB): 100%|██████████| 101/101 [00:01<00:00, 99.72it/s]
Caching labels (101 found, 0 missing, 0 empty, 0 duplicate, for 101 images): 100%|██████████| 101/101 [00:00<00:00, 426.96it/s]
Caching images (0.1GB): 100%|██████████| 101/101 [00:01<00:00, 68.68it/s]
/usr/lib/python3.10/multiprocessing/popen_fork.py:66: RuntimeWarning: os.fork() was called. os.fork() is incompatible with multithreaded code, and JAX is multithreaded, so this will likely lead to a deadlock.
  self.pid = os.fork()
  0%|          | 0/11 [00:00<?, ?it/s]/content/gdrive/MyDrive/ERA/S12YoloV3/YoloV3/utils/utils.py:374: UserWarning: The torch.cuda.*DtypeTensor constructors are no longer recommended. It's best to use methods such as torch.tensor(data, dtype=*, device='cuda') to create tensors. (Triggered internally at ../torch/csrc/tensor/python_tensor.cpp:83.)
  lcls, lbox, lobj = ft([0]), ft([0]), ft([0])
/usr/local/lib/python3.10/dist-packages/torch/cuda/memory.py:440: FutureWarning: torch.cuda.memory_cached has been renamed to torch.cuda.memory_reserved
  warnings.warn(
     0/279     7.74G      7.73       161         0       169        25       512:   9%|▉         | 1/11 [00:06<01:07,  6.72s/it]/usr/local/lib/python3.10/dist-packages/torch/cuda/memory.py:440: FutureWarning: torch.cuda.memory_cached has been renamed to torch.cuda.memory_reserved
  warnings.warn(
     0/279      7.8G      7.12      75.6         0      82.7         2       512: 100%|██████████| 11/11 [00:13<00:00,  1.27s/it]
/usr/local/lib/python3.10/dist-packages/torch/functional.py:507: UserWarning: torch.meshgrid: in an upcoming release, it will be required to pass the indexing argument. (Triggered internally at ../aten/src/ATen/native/TensorShape.cpp:3549.)
  return _VF.meshgrid(tensors, **kwargs)  # type: ignore[attr-defined]
               Class    Images   Targets         P         R   mAP@0.5        F1:   0%|          | 0/11 [00:00<?, ?it/s]/usr/lib/python3.10/multiprocessing/popen_fork.py:66: RuntimeWarning: os.fork() was called. os.fork() is incompatible with multithreaded code, and JAX is multithreaded, so this will likely lead to a deadlock.
  self.pid = os.fork()
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:05<00:00,  2.07it/s]
     1/279     13.1G      6.71      5.97         0      12.7         4       512: 100%|██████████| 11/11 [00:07<00:00,  1.41it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:04<00:00,  2.36it/s]
     2/279       15G      5.63      4.23         0      9.86         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.36it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
     3/279       15G      4.66      4.68         0      9.34         2       512: 100%|██████████| 11/11 [00:07<00:00,  1.39it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
     4/279       15G      4.98      5.47         0      10.4         6       512: 100%|██████████| 11/11 [00:07<00:00,  1.40it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.47it/s]
     5/279       15G      4.87      4.32         0      9.19         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
     6/279       15G      4.37       4.5         0      8.88         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.36it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
     7/279       15G      4.13      2.88         0      7.01         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.37it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.53it/s]
     8/279       15G      4.55      2.28         0      6.83         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
     9/279       15G      3.94      1.67         0       5.6         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.86it/s]
    10/279       15G       5.1      1.89         0      6.98         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.37it/s]
    11/279       15G      3.56      1.41         0      4.97         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
    12/279       15G       3.8      1.44         0      5.25         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.86it/s]
    13/279       15G      3.75      1.17         0      4.92         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.28it/s]
    14/279       15G      3.68      1.15         0      4.82         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.75it/s]
    15/279       15G      3.65      1.05         0       4.7         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.89it/s]
    16/279       15G      3.46      1.12         0      4.59         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.75it/s]
    17/279       15G      3.15      1.13         0      4.28         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.34it/s]
    18/279       15G      3.47      1.24         0       4.7         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
    19/279       15G      3.02      1.06         0      4.08         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.87it/s]
    20/279       15G      3.33      1.15         0      4.48         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.34it/s]
    21/279       15G       3.5     0.946         0      4.44         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.79it/s]
    22/279       15G      3.41     0.982         0      4.39         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.27it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
    23/279       15G       3.2     0.829         0      4.03         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.75it/s]
    24/279       15G      3.22     0.917         0      4.13         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.40it/s]
    25/279       15G      3.29     0.854         0      4.14         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
    26/279       15G      3.29     0.878         0      4.17         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.50it/s]
    27/279       15G      3.07      1.07         0      4.13         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.30it/s]
    28/279       15G      2.82     0.889         0      3.71         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
    29/279       15G      2.69     0.923         0      3.61         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
    30/279       15G      3.32     0.862         0      4.19         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.74it/s]
    31/279       15G      3.14     0.868         0      4.01         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.44it/s]
    32/279       15G      3.33     0.868         0       4.2         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
    33/279       15G      2.76      1.06         0      3.81         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
    34/279       15G       3.2     0.848         0      4.05         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.37it/s]
    35/279       15G      2.89     0.851         0      3.74         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.78it/s]
    36/279       15G      2.91     0.822         0      3.73         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
    37/279       15G      2.95     0.915         0      3.86         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.76it/s]
    38/279       15G      3.02     0.853         0      3.87         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.44it/s]
    39/279       15G      2.61     0.939         0      3.55         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
    40/279       15G       2.6     0.964         0      3.57         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
    41/279       15G      2.55     0.794         0      3.35         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.39it/s]
    42/279       15G      2.78     0.959         0      3.74         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.76it/s]
    43/279       15G      2.76     0.869         0      3.62         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
    44/279       15G      2.77         1         0      3.77         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
    45/279       15G      2.66     0.851         0      3.51         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.39it/s]
    46/279       15G       2.6     0.798         0       3.4         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
    47/279       15G      2.61     0.879         0      3.49         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
    48/279       15G      2.62     0.784         0       3.4         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.31it/s]
    49/279       15G      2.29     0.921         0      3.21         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
    50/279       15G      2.65     0.808         0      3.46         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.78it/s]
    51/279       15G      2.36     0.766         0      3.12         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.42it/s]
    52/279       15G      2.68     0.711         0      3.39         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
    53/279       15G      2.43     0.737         0      3.16         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
    54/279       15G      2.54      0.73         0      3.27         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.44it/s]
    55/279       15G      2.35     0.804         0      3.16         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.74it/s]
    56/279       15G      2.72     0.749         0      3.47         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
    57/279       15G      2.56     0.809         0      3.37         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
    58/279       15G      2.17     0.738         0      2.91         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.46it/s]
    59/279       15G      2.58     0.722         0       3.3         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
    60/279       15G      2.47     0.894         0      3.36         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
    61/279       15G      2.55     0.736         0      3.29         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.31it/s]
    62/279       15G      2.49     0.724         0      3.21         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
    63/279       15G      2.22     0.695         0      2.92         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
    64/279       15G      2.41      0.84         0      3.25         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.77it/s]
    65/279       15G      2.35     0.746         0       3.1         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.51it/s]
    66/279       15G      2.22     0.742         0      2.96         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
    67/279       15G      2.39     0.833         0      3.23         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
    68/279       15G      2.04     0.852         0      2.89         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.38it/s]
    69/279       15G      2.16      0.73         0      2.89         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
    70/279       15G      2.23      0.71         0      2.94         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.23it/s]
    71/279       15G      2.14     0.723         0      2.87         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.82it/s]
    72/279       15G      1.83     0.686         0      2.52         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.38it/s]
    73/279       15G      2.12     0.686         0       2.8         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
    74/279       15G      2.37     0.746         0      3.12         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.89it/s]
    75/279       15G      2.19      0.66         0      2.85         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.34it/s]
    76/279       15G      2.15     0.786         0      2.94         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.82it/s]
    77/279       15G      2.06     0.699         0      2.76         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.85it/s]
    78/279       15G      2.18     0.642         0      2.82         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.87it/s]
    79/279       15G      1.95     0.682         0      2.63         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.48it/s]
    80/279       15G         2     0.721         0      2.73         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
    81/279       15G      1.81     0.616         0      2.43         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
    82/279       15G      1.72      0.77         0      2.49         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.41it/s]
    83/279       15G      2.05     0.797         0      2.85         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
    84/279       15G      1.87     0.668         0      2.53         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
    85/279       15G       1.9     0.688         0      2.58         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.76it/s]
    86/279       15G      1.93     0.781         0      2.71         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.49it/s]
    87/279       15G      1.83     0.613         0      2.45         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
    88/279       15G      2.03     0.655         0      2.68         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
    89/279       15G      1.74     0.631         0      2.38         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.35it/s]
    90/279       15G       1.6     0.589         0      2.18         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.77it/s]
    91/279       15G      1.86     0.775         0      2.63         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.69it/s]
    92/279       15G      1.73     0.685         0      2.42         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
    93/279       15G      1.72     0.764         0      2.49         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.45it/s]
    94/279       15G      1.98     0.758         0      2.73         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
    95/279       15G      1.61     0.624         0      2.23         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
    96/279       15G      1.64     0.604         0      2.24         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.43it/s]
    97/279       15G      1.75     0.676         0      2.42         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.86it/s]
    98/279       15G      1.68     0.638         0      2.32         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
    99/279       15G      1.73     0.646         0      2.37         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
   100/279       15G      1.96     0.653         0      2.61         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.34it/s]
   101/279       15G      1.57     0.543         0      2.11         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
   102/279       15G      1.73      0.59         0      2.32         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   103/279       15G      1.88     0.607         0      2.48         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.38it/s]
   104/279       15G      1.65     0.584         0      2.24         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   105/279       15G      1.91     0.677         0      2.58         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
   106/279       15G      1.61     0.618         0      2.23         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.75it/s]
   107/279       15G      1.63     0.518         0      2.15         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.42it/s]
   108/279       15G      1.77     0.599         0      2.37         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
   109/279       15G      1.61     0.537         0      2.15         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
   110/279       15G      1.69     0.613         0       2.3         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.35it/s]
   111/279       15G      1.51     0.642         0      2.15         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.77it/s]
   112/279       15G      1.63     0.549         0      2.18         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
   113/279       15G      1.91     0.685         0       2.6         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.25it/s]
   114/279       15G      1.72     0.549         0      2.27         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
   115/279       15G      1.63      0.54         0      2.17         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.87it/s]
   116/279       15G      1.58     0.619         0       2.2         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
   117/279       15G       1.6     0.595         0      2.19         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.49it/s]
   118/279       15G      1.62     0.561         0      2.18         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
   119/279       15G       1.6     0.604         0       2.2         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
   120/279       15G      1.35     0.526         0      1.88         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.49it/s]
   121/279       15G      1.43     0.599         0      2.03         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   122/279       15G      1.61     0.608         0      2.22         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   123/279       15G      1.61     0.541         0      2.15         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.76it/s]
   124/279       15G      1.44     0.538         0      1.98         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.40it/s]
   125/279       15G       1.5     0.537         0      2.03         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.89it/s]
   126/279       15G      1.56      0.48         0      2.04         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
   127/279       15G      1.62     0.567         0      2.19         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.35it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.38it/s]
   128/279       15G      1.69     0.488         0      2.18         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.78it/s]
   129/279       15G      1.38     0.517         0       1.9         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   130/279       15G      1.46     0.549         0      2.01         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   131/279       15G      1.49     0.615         0      2.11         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.44it/s]
   132/279       15G      1.45     0.541         0      1.99         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   133/279       15G      1.33      0.57         0       1.9         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
   134/279       15G      1.49     0.654         0      2.15         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.18it/s]
   135/279       15G       1.4     0.558         0      1.95         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
   136/279       15G      1.31     0.571         0      1.88         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.77it/s]
   137/279       15G      1.54      0.53         0      2.07         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.51it/s]
   138/279       15G      1.57      0.54         0      2.11         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
   139/279       15G      1.49     0.784         0      2.27         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   140/279       15G      1.43     0.497         0      1.93         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.43it/s]
   141/279       15G      1.48     0.613         0       2.1         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.85it/s]
   142/279       15G      1.52     0.589         0      2.11         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   143/279       15G      1.53     0.559         0      2.09         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   144/279       15G      1.57     0.562         0      2.14         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.40it/s]
   145/279       15G       1.3     0.547         0      1.85         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.87it/s]
   146/279       15G       1.3     0.508         0       1.8         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   147/279       15G      1.56     0.578         0      2.14         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.37it/s]
   148/279       15G      1.29     0.536         0      1.83         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.78it/s]
   149/279       15G      1.27     0.549         0      1.82         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
   150/279       15G       1.4      0.44         0      1.84         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.78it/s]
   151/279       15G      1.45     0.557         0      2.01         7       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.40it/s]
   152/279       15G      1.28     0.469         0      1.74         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.99it/s]
   153/279       15G      1.39     0.464         0      1.85         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   154/279       15G      1.19      0.41         0       1.6         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.40it/s]
   155/279       15G      1.36     0.529         0      1.89         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   156/279       15G      1.23     0.415         0      1.65         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   157/279       15G      1.34     0.531         0      1.88         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.44it/s]
   158/279       15G      1.23     0.489         0      1.72         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
   159/279       15G      1.31     0.481         0       1.8         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
   160/279       15G      1.28     0.466         0      1.74         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.79it/s]
   161/279       15G      1.04     0.399         0      1.44         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.49it/s]
   162/279       15G      1.15     0.481         0      1.63         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
   163/279       15G       1.3     0.516         0      1.82         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.99it/s]
   164/279       15G      1.08     0.389         0      1.47         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.35it/s]
   165/279       15G      1.21     0.516         0      1.72         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.71it/s]
   166/279       15G      1.19      0.51         0       1.7         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
   167/279       15G      1.02     0.423         0      1.44         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   168/279       15G      1.18     0.436         0      1.62         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.46it/s]
   169/279       15G      1.05     0.462         0      1.51         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   170/279       15G      1.01     0.527         0      1.54         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
   171/279       15G       1.1     0.417         0      1.52         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.39it/s]
   172/279       15G      1.19     0.477         0      1.67         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
   173/279       15G      1.21     0.506         0      1.71         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
   174/279       15G     0.942     0.381         0      1.32         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
   175/279       15G      1.07     0.401         0      1.47         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.53it/s]
   176/279       15G      1.08      0.45         0      1.53         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
   177/279       15G      1.02     0.491         0      1.52         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.64it/s]
   178/279       15G     0.933     0.375         0      1.31         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.49it/s]
   179/279       15G     0.978     0.379         0      1.36         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
   180/279       15G      1.08     0.454         0      1.54         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  5.00it/s]
   181/279       15G      1.05     0.447         0      1.49         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.42it/s]
   182/279       15G      1.18     0.441         0      1.62         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
   183/279       15G      1.02     0.411         0      1.44         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
   184/279       15G      1.14     0.425         0      1.56         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.87it/s]
   185/279       15G      1.29     0.438         0      1.73         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.49it/s]
   186/279       15G      1.14     0.377         0      1.51         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   187/279       15G       1.3      0.45         0      1.75         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
   188/279       15G      1.14     0.409         0      1.55         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.46it/s]
   189/279       15G      1.14     0.427         0      1.57         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.82it/s]
   190/279       15G      1.03      0.41         0      1.44         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   191/279       15G      1.26     0.417         0      1.68         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
   192/279       15G      1.04       0.4         0      1.44         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.50it/s]
   193/279       15G      1.12      0.41         0      1.53         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
   194/279       15G     0.869     0.401         0      1.27         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   195/279       15G     0.984     0.386         0      1.37         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.35it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.39it/s]
   196/279       15G     0.931     0.484         0      1.41         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.84it/s]
   197/279       15G      1.01     0.414         0      1.42         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   198/279       15G      1.05     0.424         0      1.48         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.13it/s]
   199/279       15G     0.993      0.42         0      1.41         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   200/279       15G     0.967     0.346         0      1.31         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   201/279       15G     0.814      0.39         0       1.2         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
   202/279       15G      1.02     0.404         0      1.42         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.49it/s]
   203/279       15G     0.921     0.524         0      1.44         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
   204/279       15G     0.814      0.43         0      1.24         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
   205/279       15G      1.04     0.407         0      1.45         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.43it/s]
   206/279       15G      1.05     0.413         0      1.46         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
   207/279       15G      1.05     0.376         0      1.43         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
   208/279       15G     0.997     0.438         0      1.44         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
   209/279       15G     0.917     0.399         0      1.32         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.47it/s]
   210/279       15G     0.878     0.369         0      1.25         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   211/279       15G      0.95     0.349         0       1.3         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   212/279       15G     0.865     0.402         0      1.27         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.48it/s]
   213/279       15G     0.965     0.368         0      1.33         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   214/279       15G     0.953     0.394         0      1.35         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   215/279       15G     0.931     0.393         0      1.32         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.82it/s]
   216/279       15G      0.98      0.32         0       1.3         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.45it/s]
   217/279       15G     0.764     0.368         0      1.13         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   218/279       15G     0.946     0.329         0      1.28         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.89it/s]
   219/279       15G     0.947     0.348         0      1.29         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.35it/s]
   220/279       15G     0.798     0.293         0      1.09         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
   221/279       15G     0.826     0.366         0      1.19         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.86it/s]
   222/279       15G     0.866      0.42         0      1.29         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.42it/s]
   223/279       15G      1.02     0.373         0      1.39         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
   224/279       15G     0.788     0.408         0       1.2         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   225/279       15G     0.821     0.426         0      1.25         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
   226/279       15G     0.801     0.306         0      1.11         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.44it/s]
   227/279       15G     0.846     0.343         0      1.19         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
   228/279       15G     0.778     0.317         0      1.09         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
   229/279       15G     0.819     0.366         0      1.18         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.40it/s]
   230/279       15G     0.791     0.395         0      1.19         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.90it/s]
   231/279       15G     0.848     0.427         0      1.27         8       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
   232/279       15G      0.92     0.346         0      1.27         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.77it/s]
   233/279       15G     0.806     0.338         0      1.14         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.47it/s]
   234/279       15G     0.683     0.287         0      0.97         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   235/279       15G     0.714     0.311         0      1.03         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
   236/279       15G      0.94     0.304         0      1.24         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.41it/s]
   237/279       15G     0.851     0.375         0      1.23         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
   238/279       15G     0.803     0.356         0      1.16         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.26it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
   239/279       15G     0.719     0.401         0      1.12         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.88it/s]
   240/279       15G     0.747     0.315         0      1.06         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.31it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.49it/s]
   241/279       15G     0.816     0.318         0      1.13         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
   242/279       15G     0.732     0.338         0      1.07         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   243/279       15G     0.778     0.305         0      1.08         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.38it/s]
   244/279       15G     0.902     0.367         0      1.27         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.86it/s]
   245/279       15G      0.77     0.364         0      1.13         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]
   246/279       15G     0.851     0.312         0      1.16         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.85it/s]
   247/279       15G     0.763      0.37         0      1.13         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.45it/s]
   248/279       15G       0.7     0.379         0      1.08         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   249/279       15G     0.796     0.296         0      1.09         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
   250/279       15G     0.712     0.347         0      1.06         5       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.37it/s]
   251/279       15G     0.624     0.327         0     0.951         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.79it/s]
   252/279       15G     0.717     0.321         0      1.04         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
   253/279       15G     0.774     0.332         0      1.11         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.76it/s]
   254/279       15G     0.857     0.276         0      1.13         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.38it/s]
   255/279       15G     0.675     0.296         0     0.972         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.93it/s]
   256/279       15G     0.811     0.395         0      1.21         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.98it/s]
   257/279       15G     0.735     0.258         0     0.993         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.31it/s]
   258/279       15G     0.667     0.362         0      1.03         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.80it/s]
   259/279       15G     0.771     0.352         0      1.12         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
   260/279       15G     0.737     0.316         0      1.05         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.19it/s]
   261/279       15G     0.714     0.297         0      1.01         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.28it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.82it/s]
   262/279       15G     0.652     0.276         0     0.927         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.97it/s]
   263/279       15G      0.76     0.316         0      1.08         6       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.83it/s]
   264/279       15G     0.735     0.382         0      1.12         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.39it/s]
   265/279       15G     0.742     0.307         0      1.05         1       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.96it/s]
   266/279       15G     0.687     0.349         0      1.04         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.94it/s]
   267/279       15G     0.735     0.283         0      1.02         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.49it/s]
   268/279       15G     0.562     0.331         0     0.893         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   269/279       15G     0.721     0.351         0      1.07         7       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.92it/s]
   270/279       15G     0.643     0.345         0     0.988         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.79it/s]
   271/279       15G     0.675     0.327         0         1         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.43it/s]
   272/279       15G     0.647     0.344         0     0.991         2       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.82it/s]
   273/279       15G     0.684     0.327         0      1.01         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.30it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   274/279       15G     0.739      0.32         0      1.06         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.32it/s]
   275/279       15G     0.694     0.352         0      1.05         7       512: 100%|██████████| 11/11 [00:08<00:00,  1.32it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.81it/s]
   276/279       15G     0.752     0.342         0      1.09         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.91it/s]
   277/279       15G       0.5     0.323         0     0.823         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.33it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.82it/s]
   278/279       15G     0.619     0.269         0     0.888         3       512: 100%|██████████| 11/11 [00:08<00:00,  1.34it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.51it/s]
   279/279       15G     0.681     0.314         0     0.995         4       512: 100%|██████████| 11/11 [00:08<00:00,  1.29it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100%|██████████| 11/11 [00:02<00:00,  4.95it/s]

