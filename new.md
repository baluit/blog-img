## Jailbreak - 9

* 数据集：advbench

* 模型：rewrite and judge model："gpt-3.5-turbo", "gpt-4"

  ​	attack_model："claude-3-5-sonnet-20241022", "gpt-4"

* 方法：ReNeLLM

* 负责人：巴蕾

* 开发完成日期：2025/2/21

* 实现代码：

  * ```python
    python examples/jailbreak.py --attack ReNeLLM --model-path /home/balei/models/vicuna/vicuna-13b-v1.5/ ReNeLLM --gpt_api_key sk-... --gpt_base_url ... --claude_api_key sk-... --claude_base_url ...
    ```

* 实现效果：

  * 

    ![image-20250221165109695](assets/image-20250221165109695.png)

    攻击结果示例：`judge_by_gpt-3.5-turbo_attack_on_claude-3-5-sonnet-20241022_normal.json`

    ![image-20250221162852510](assets/image-20250221162852510.png)

# 
