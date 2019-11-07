CU Boulder ChangeMyView Comment Removal Data v1.0 (released October, 2019)

Distributed together with:

Content removal as a moderation strategy: Compliance and other outcomes in the ChangeMyView community   
Kumar Bhargav Srinivasan, Cristian Danescu-Niculescu-Mizil, Lillian Lee, and Chenhao Tan.   
In Proceedings of the Conference on Computer-Supported Cooperative Work and Social Computing (CSCW'2019).   
The paper, data, and associated materials can be found at:
<https://chenhaot.com/papers/content-removal.html>.

If you use this data, please cite:

@inproceedings{srinivasan+dnm+lee+tan:19,   
&nbsp;&nbsp;&nbsp;&nbsp;     author = {Kumar Bhargav Srinivasan and Cristian Danescu-Niculescu-Mizil and Lillian Lee and Chenhao Tan},   
&nbsp;&nbsp;&nbsp;&nbsp;     title = {Content removal as a moderation strategy: Compliance and other outcomes in the ChangeMyView community},   
&nbsp;&nbsp;&nbsp;&nbsp;     year = {2019},   
&nbsp;&nbsp;&nbsp;&nbsp;     booktitle = {Proceedings of CSCW}   
}

This dataset consists of five files that can be used to find the relevant comments used for all the analyses in the paper.

Each file is a compressed jsonlist file where each line is a json object.

- Interrupted time-series analysis in non-affected trees: _its\_dataset.json.gz_, each line consists of comment ids before removal and after removal, removed comment id, author id.
- Applying the delayed feedback approach in non affected trees:  _delayed\_feedback\_setup\_non\_treatment\_trees.json.gz_, each line consists of treatment author id, control author id, treatment removed comment id, control removed comment id, treamtent before removal comment id, treatment after removal comment id, control before virtual removal comment id, and control after virtual removal comment id.
- Delayed feedback in affected trees: _delayed\_feedback\_setup\_treatment\_trees.json.gz_, each line consists of treatment author id, control author id, treatment removed comment id, control removed comment id, treamtent before removal comment id, treatment after removal comment id, control before virtual removal comment id, and control after virtual removal comment id.
- First and second removals of an author: _first\_and\_second\_removals.json.gz_, each line consists of comment id, author id, and link id.
- First removals of an author: _first\_removals.json.gz_,  each line consists of comment id, author id, and link id.
