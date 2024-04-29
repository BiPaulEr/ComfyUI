git clone in custonnodes https://github.com/ltdrdata/ComfyUI-Manager
in the manager custom nodes : 	
- install Fannovel16	 ComfyUI's ControlNet Auxiliary Preprocessors
- install ComfyMath
- install Recommended Resolution Calculator
- install UltimateSDUpscale   : Pas besion 
- install ComfyUI-VideoHelperSuite
- install ComfyUI-AnimateDiff-Evolved
- comfyui-optical-flow
- sdxl-recommended-res-calc
- submodule

Download : pythorch_model.bin https://huggingface.co/openai/clip-vit-large-patch14/tree/main à mettre dans clip_vision

Download : https://huggingface.co/TencentARC/T2I-Adapter/tree/main/models coadapter-style-sd15v1.pth + t2iadapter_style_sd14v1.pth in style_models
le reste dans control net

Download animate diff mm_sdxl_v10 : https://huggingface.co/guoyww/animatediff/tree/cd71ae134a27ec6008b968d6419952b0c0494cf2

git clone https://github.com/Kosinkadink/ComfyUI-Advanced-ControlNet.git in custom nodes for ControlNEt advanced -> required for Animatediff