# Fine-Tuning DeepSeek-R1-Distill-Qwen-1.5B

This repository contains Jupyter notebooks for fine-tuning and testing the **DeepSeek-R1-Distill-Qwen-1.5B** model.

## Repository Structure

- **DeepSeek_FineTune.ipynb**: Jupyter notebook for fine-tuning the DeepSeek-R1-Distill-Qwen-1.5B model.
- **Test_Modal.ipynb**: Jupyter notebook to evaluate the performance of the fine-tuned model.

## Requirements

Before running the notebooks, install the required dependencies:

```bash
pip install torch transformers datasets peft accelerate bitsandbytes
```

Make sure you have a compatible GPU and CUDA installed for efficient training.

## Fine-Tuning Process

1. Load the pre-trained **DeepSeek-R1-Distill-Qwen-1.5B** model.
2. Prepare and preprocess the dataset.
3. Apply PEFT (Parameter Efficient Fine-Tuning) techniques for optimizing training.
4. Train the model using the **DeepSeek_FineTune.ipynb** notebook.
5. Save the fine-tuned model.

## Testing the Fine-Tuned Model

1. Load the fine-tuned model.
2. Run inference using test inputs.
3. Evaluate model performance using **Test_Modal.ipynb**.

## Usage

To fine-tune the model, open **DeepSeek_FineTune.ipynb** in Jupyter Notebook or Google Colab and execute the cells sequentially.

To test the model, open **Test_Modal.ipynb** and run the inference code.

## License

This project is open-source and available under the MIT License.

---

Feel free to contribute or raise issues if you encounter any problems!

