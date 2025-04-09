# Tree of Thought demo
Run baseline experiments on Game24 independently and use Tree of Thoughts on a single example to demonstrate usage.

Paper repository: [GitHub](https://github.com/princeton-nlp/tree-of-thought-llm/tree/master)

## Experiments
Simple experiments on 100 random samples. Total run time for ToT is approx. 1 hour on a Macbook Pro.

| Method     | Success   | Runs |
| --------   | --------  | ---- |
| IO prompt  | 10%       | 1    |
| CoT prompt | 26%       | 1    |
| ToT (b=1)  | 50%       | 1    |

## Citations

```bibtex
@misc{yao2023tree,
      title={{Tree of Thoughts}: Deliberate Problem Solving with Large Language Models}, 
      author={Shunyu Yao and Dian Yu and Jeffrey Zhao and Izhak Shafran and Thomas L. Griffiths and Yuan Cao and Karthik Narasimhan},
      year={2023},
      eprint={2305.10601},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
