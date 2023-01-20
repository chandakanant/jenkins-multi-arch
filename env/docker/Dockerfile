# FROM jenkins/jenkins:2.319.3-jdk11
# RUN jenkins-plugin-cli --plugins \      
#         configuration-as-code:1512.vb_79d418d5fc8 \
#         kubernetes:1.31.3 \
#         workflow-aggregator:581.v0c46fa_697ffd \
#         git:4.11.0 \
#         extended-choice-parameter:346.vd87693c5a_86c \
#         google-chat-notification:1.4 \
#         role-strategy:561.v9846c7351a_41 \
#         email-ext:2.89
FROM jenkins/jenkins:2.319.3-jdk11
RUN jenkins-plugin-cli --plugins \
        kubernetes \
        workflow-aggregator \
        git \
        configuration-as-code \
        role-strategy \
        google-chat-notification \
        email-ext \
        oic-auth
