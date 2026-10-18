# Wazuh 集成指南

## 前置条件
- Wazuh Manager 4.x 已部署
- TSG 网关 v4.33+ 运行中

## 对接步骤
1. 配置 TSG 审计日志输出到 Wazuh
2. 在 Wazuh 规则库添加 TSG 自定义规则
3. 验证告警触发

## 测试 checklist
- [ ] 模拟攻击产生日志
- [ ] Wazuh  Dashboard 可见告警
