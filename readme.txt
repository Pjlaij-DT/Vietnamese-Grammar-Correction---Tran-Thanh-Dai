* Ở yêu cầu 1, bài nộp source code gồm 1 file:
	* nlp_final_ex1_bpe: Chứa mô hình và tiến trình huấn luyện, file tune
	* Model được file-tune: t5-small (https://huggingface.co/google-t5/t5-small)
	* Đường link Google Drive chứa checkpoint sau fine-tune của model  có sử dụng BPE: 		https://drive.google.com/drive/folders/16AYwFe8HixEXPzXckxWuz0c1QTqzlZlZ?usp=drive_link
	* Đường link Google Drive chứa checkpoint sau fine-tune của model không có sử dung BPE:
	https://drive.google.com/drive/folders/153ypL2G8ayS6r_OQr_O9sGn_iebAkWGF?usp=drive_link
	* Cách lấy model để chạy:
		* Truy cập đường link google drive này: https://drive.google.com/drive/folders/1RPvutped8Hj3IhV_KB3TQ5gHtKs7RVkO?usp=drive_link
		* Tạo một shortcut dẫn đến My Drive của tài khoản Google Drive của mình (chuột phải -> Organize -> Add Shortcut -> My Drive)
		* Chạy code kèm theo

* Ở yêu cầu 2, bài nộp source code gồm 2 file:
	* BASIC_GRAMMAR: Sử dung cấu trúc Seq2Seq, chúng em đã tự định nghĩa và huấn luyện một mô hình sửa lỗi chính tả trong tiếng Việt, tuy nhiên, do lượng dữ liệu và thời gian huấn luyện trên Google Colab bị giới hạn, cũng như hiệu suất của model còn kém, đã không đưa ra được kết quả tốt. Tuy nhiên, chúng em xin nộp file này như proof of concept.
	* Fine_tune_GRAMMAR: Finetune từ model BART-Pho (https://huggingface.co/docs/transformers/en/model_doc/bartpho), sử dụng dữ liệu sưu tầm và thực hiện biến đổi dữ liệu tạo những lỗi chính tả.
	* Cách lấy model để chạy:
		* Truy cập đường link google drive này: https://drive.google.com/drive/folders/1RPvutped8Hj3IhV_KB3TQ5gHtKs7RVkO?usp=drive_link
		* Tạo một shortcut dẫn đến My Drive của tài khoản Google Drive của mình (chuột phải -> Organize -> Add Shortcut -> My Drive)
		* Chạy code kèm theo