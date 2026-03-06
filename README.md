# UIC Thesis

## Thesis Summary

The rapid growth of LLM-based applications, such as chatbots, coding assistants, and search engines, has driven the need to deliver LLM inference at scale. This workload is highly resource-demanding, requiring substantial compute throughput along with large, high-bandwidth memory. As a result, efficient LLM serving often depends on specialized hardware acceleration. While GPUs continue to dominate, domain-specific accelerators like TPUs and dataflow architectures are becoming increasingly compelling alternatives.

This thesis provides a comprehensive empirical performance study of six datacenter-grade GPUs from NVIDIA, AMD, and Intel, along with two dataflow AI accelerators from Cerebras and SambaNova, evaluated across fourteen open-source LLMs. The analysis examines key factors that influence LLM inference performance, including model size, batch size, quantization, and multi-GPU scaling across different parallelism strategies. Crucially, it evaluates both performance and energy efficiency to provide an energy-aware comparison across accelerator classes.

The findings show that dataflow AI accelerators deliver an order-of-magnitude speedup in throughput and latency for small batch sizes relative to GPUs. Conversely, GPUs provide larger HBM memory capacities and benefit from a more straightforward programming model, enabling greater flexibility in batch sizing.

Together, these results offer actionable insights for optimizing LLM inference across a range of deployment settings.

## Code Repository

Code and related artifacts are available at:

- https://github.com/SPEAR-UIC/IPDPS26-LLM-Energy.git

## Accessibility

For accessibility reasons, you can use the EPUB version of the thesis ("ebup" version): `thesis.epub`.
