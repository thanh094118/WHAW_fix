# cài dependent:
clone về  
pip install -r requirements.txt  

# thêm code:
folder: utils  

# thay code:
demo.py  
lib/models/preproc/detector.py  
lib/models/wham.py  
# file cấu hình:
down tại: https://drive.google.com/file/d/15qdj3iFyyiFC6Sre0i0NZxXCymER-pJj/view?usp=sharing  
đặt tại: checkpoints/vitpose+_huge_wholebody/wholebody.pth  
# lệnh chạy:
python demo.py --video examples/video_input.mp4 --estimate_local_only --save_pkl --output_pth output

