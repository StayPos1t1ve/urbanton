# urbanton
1. pip install torch -f https://download.pytorch.org/whl/torch_stable.html
2. pip install diffusers
3. pip install opencv-python pycocotools matplotlib onnxruntime onnx
4. pip install git+https://github.com/facebookresearch/segment-anything.git
5. pip install numpy
6. pip install matplotlib

# ЗАПУСК
   ## 
   python inpainting.py --get_topk --image_path images/conder.jpg --text_prompt conditioner --inpaint_prompt "wipe out conditioners" -o outputs/ --device cuda:0
