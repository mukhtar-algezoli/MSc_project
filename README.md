# MSc_project
The dataset splits were downloaded from: https://www.openslr.org/12

The alignment files are available at: https://drive.google.com/drive/folders/1n53BGCrmw3w_6p07RckfxvFyqpdhmWoi?usp=sharing.

Those notebooks were designed to work on Google Colab, so make sure to modify the path if you want to run them locally.

To run the whole pipeline for each model as described in the dissertation, Run those files in order:
generate_representations2.ipynp -> create_subspace_matrices.ipynp -> apply_projection_new.ipynp -> dump_files_in_one_filelist2.ipynp

To run the evaluation:
ABX.ipynp
linear_sep_test.ipynp

