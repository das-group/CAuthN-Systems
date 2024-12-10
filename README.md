<h1>Appendix to SoK: Continuous Authentication Beyond Error Rates: Reviewing General System Properties</h1>

<table>
    <tr>
      <td><b>System</b></td>
        <td><b>Use case</b></td>
        <td><b>Resource to be secured</b></td>
        <td><b>Attacker model</b></td>
        <td><b>Deployment scheme, location of enrollment</b></td>
        <td><b>Deployment scheme, location of authentication</b></td>
        <td><b>Algorithmic approach</b></td>
      <td><b>Privacy measures</b></br><small>Entries marked with * are considered to be misconceptions</small></td>
        <td><b>System response after failed authentication</b></td>
        <td><b>Re-authentication strategie</b></td>
    </tr>
    <tr>
        <td>Mahfouz, A., Hamdy, A., Eldin, M. A., &amp; Mahmoud, T. M. (2024). B2auth: A contextual fine-grained behavioral biometric authentication framework for real-world deployment. Pervasive and Mobile Computing, 101888. https://doi.org/10.1016/j.pmcj.2024.101888</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Client</td>
        <td>Classification</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Li, Y., Huang, Y., &amp; Huang, H. (2024). FuMeAuth: Sensor-Based Continuous Authentication Using Fused Memory-Augmented Transformer Autoencoder. IEEE Internet of Things Journal, 1–1. https://doi.org/10.1109/JIOT.2024.3394437</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td></td>
        <td>Lock the device</td>
        <td></td>
    </tr>
    <tr>
        <td>Li, Y., Liu, L., Deng, S., Qin, H., El-Yacoubi, M. A., &amp; Zhou, G. (2024). Memory-Augmented Autoencoder Based Continuous Authentication on Smartphones With Conditional Transformer GANs. IEEE Transactions on Mobile Computing, 23(5), 4467–4482. https://doi.org/10.1109/TMC.2023.3290834</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td></td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Alawami, M. A., Abuhmed, T., Abuhamad, M., &amp; Kim, H. (2024). MotionID: Towards practical behavioral biometrics-based implicit user authentication on smartphones. Pervasive and Mobile Computing, 101, 101922. https://doi.org/10.1016/j.pmcj.2024.101922</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td></td>
        <td>Lock the device</td>
        <td></td>
    </tr>
    <tr>
        <td>Li, Y., Ouyang, C., &amp; Huang, H. (2024). AEGANAuth: Autoencoder GAN-Based Continuous Authentication With Conditional Variational Autoencoder Generative Adversarial Network. IEEE Internet of Things Journal, 11(16), 27635–27650. IEEE Internet of Things Journal. https://doi.org/10.1109/JIOT.2024.3399549</td>
        <td>General mobile devices</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td></td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Lopez, J. M. E., Celdran, A. H., Esquembre, F., Perez, G. M., &amp; Marin-Blazquez, J. G. (2023). CGAPP: A continuous group authentication privacy-preserving platform for industrial scene. JOURNAL OF INFORMATION SECURITY AND APPLICATIONS, 78, 103622. https://doi.org/10.1016/j.jisa.2023.103622</td>
        <td>Smartphone app in enterprise environment</td>
        <td>Client App</td>
        <td>Unspecified</td>
        <td>Client / Server</td>
        <td>Client</td>
        <td>Classification</td>
        <td>Discussed but not implemented</td>
        <td>Lock the device, report to the management, undo the last action</td>
        <td></td>
    </tr>
    <tr>
        <td>Fereidooni, H., Koenig, J., Rieger, P., Chilese, M., Goekbakan, B., Finke, M., Dmitrienko, A., & Sadeghi, A.-R. (2023). AuthentiSense: A Scalable Behavioral Biometrics Authentication Scheme using Few-Shot Learning for Mobile Platforms. Proceedings 2023 Network and Distributed System Security Symposium. Network and Distributed System Security Symposium, San Diego, CA, USA. https://doi.org/10.14722/ndss.2023.23194
</td>
        <td>General smartphone apps</td>
        <td>Cloud resource</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td></td>
        <td></td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Yang, H., Meng, X., Zhao, X., Wang, Y., Liu, Y., Kang, X., Shen, J., &amp; Huang, W. (2023). CKDAN: Content and keystroke dual attention networks with pre-trained models for continuous authentication. In COMPUTERS &amp; SECURITY (Vol. 128). ELSEVIER ADVANCED TECHNOLOGY. https://doi.org/10.1016/j.cose.2023.103159</td>
        <td>Computer in in enterprise environment</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td></td>
        <td>Lock the device, disconnect the network, shutdown the device</td>
        <td>Explicit Authentication, help from administrator</td>
    </tr>
    <tr>
        <td>Huh, J. H., Kwag, S., Kim, I., Popov, A., Park, Y., Cho, G., Lee, J., Kim, H., &amp; Lee, C.-H. (2023). On the Long-Term Effects of Continuous Keystroke Authentication: Keeping User Frustration Low through Behavior Adaptation. In PROCEEDINGS OF THE ACM ON INTERACTIVE MOBILE WEARABLE AND UBIQUITOUS TECHNOLOGIES-IMWUT (Vol. 7, Issue 2). ASSOC COMPUTING MACHINERY. https://doi.org/10.1145/3596236</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Client</td>
        <td>Client</td>
        <td>Classification</td>
        <td>Local processing</td>
        <td>Lock the device</td>
        <td></td>
    </tr>
    <tr>
        <td>Zhang, J., Li, Z., Zhang, H., Zhang, W., Ling, Z., &amp; Yang, M. (2023). Sensor-based implicit authentication through learning user physiological and behavioral characteristics. Computer Communications, 208, 244–255. https://doi.org/10.1016/j.comcom.2023.06.016</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Client</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td>Local processing </td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Gan, W., Chen, X., Wang, W., Chen, L., Wu, J., Wang, X., He, X., &amp; Wu, F. (2022). Multi-device Continuous Authentication Mechanism Based on Homomorphic Encryption and SVM Algorithm. In X. Sun, X. Zhang, Z. Xia, &amp; E. Bertino (Eds.), Artificial Intelligence and Security (pp. 625–638). Springer International Publishing. https://doi.org/10.1007/978-3-031-06791-4_49</td>
        <td>General mobile devices and computer</td>
        <td>Client device</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Homomorphic encryption</td>
        <td>temporary block the client, restrict permissions, block the client</td>
        <td>Timeout</td>
    </tr>
    <tr>
        <td>Sahu, A. K., Sharma, S., &amp; Raja, R. (2022). Deep Learning-based Continuous Authentication for an IoT-enabled healthcare service. Computers and Electrical Engineering, 99, 107817. https://doi.org/10.1016/j.compeleceng.2022.107817</td>
        <td>Mobile devices in enterprise environment</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Keeping biometric data in enterprise networks*</td>
        <td></td>
        <td>Reassess the authentication of the user</td>
    </tr>
    <tr>
        <td>Stylios, I., Skalkos, A., Kokolakis, S., &amp; Karyda, M. (2022). BioPrivacy: A behavioral biometrics continuous authentication system based on keystroke dynamics and touch gestures. INFORMATION AND COMPUTER SECURITY, 30(5), 687–704. https://doi.org/10.1108/ICS-12-2021-0212</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Stylios, I., Skalkos, A., Kokolakis, S., &amp; Karyda, M. (2022). BioPrivacy: A behavioral biometrics continuous authentication system based on keystroke dynamics and touch gestures. INFORMATION AND COMPUTER SECURITY, 30(5), 687–704. https://doi.org/10.1108/ICS-12-2021-0212</td>
        <td>Smartphone app in enterprise environment</td>
        <td>Client App</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly Detection  / Classification</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Gupta, S., Kumar, R., Kacimi, M., &amp; Crispo, B. (2022). IDeAuth: A novel behavioral biometric-based implicit deauthentication scheme for smartphones. Pattern Recognition Letters, 157, 8–15. https://doi.org/10.1016/j.patrec.2022.03.011</td>
        <td>General smartphone apps</td>
        <td>Client App</td>
        <td>Access to client</td>
        <td>Client</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td>Local processing</td>
        <td>Sign-off the applications on the smartphone</td>
        <td></td>
    </tr>
    <tr>
        <td>Monschein, D., Peregrina Perez, J. A., Piotrowski, T., Nochta, Z., Waldhorst, O. P., &amp; Zirpins, C. (2021). Towards a Peer-to-Peer Federated Machine Learning Environment for Continuous Authentication. 2021 IEEE Symposium on Computers and Communications (ISCC), 1–6. https://doi.org/10.1109/ISCC53001.2021.9631491</td>
        <td>Cryptocurrency exchange plattforms</td>
        <td>Cloud resource</td>
        <td>Compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Format preserving encryption</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Monschein, D., &amp; Waldhorst, O. P. (2021). SPCAuth: Scalable and Privacy-Preserving Continuous Authentication for Web Applications. 2021 IEEE 46th Conference on Local Computer Networks (LCN), 281–286. https://doi.org/10.1109/LCN52139.2021.9524959</td>
        <td>General cloud service</td>
        <td>Cloud resource</td>
        <td>Compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Discussed but not implemented</td>
        <td>Backend denies actions or requests additional confirmations</td>
        <td></td>
    </tr>
    <tr>
        <td>Monschein, D., &amp; Waldhorst, O. P. (2021). SPCAuth: Scalable and Privacy-Preserving Continuous Authentication for Web Applications. 2021 IEEE 46th Conference on Local Computer Networks (LCN), 281–286. https://doi.org/10.1109/LCN52139.2021.9524959</td>
        <td>General cloud service</td>
        <td>Cloud resource</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Hernández-Álvarez, L., de Fuentes, J. M., González-Manzano, L., &amp; Hernández Encinas, L. (2021). SmartCAMPP - Smartphone-based continuous authentication leveraging motion sensors with privacy preservation. Pattern Recognition Letters, 147, 189–196. https://doi.org/10.1016/j.patrec.2021.04.013</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Format preserving encryption</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Espín López, J. M., Huertas Celdrán, A., Marín-Blázquez, J. G., Esquembre, F., &amp; Martínez Pérez, G. (2021). S3: An AI-Enabled User Continuous Authentication for Smartphones Based on Sensors, Statistics and Speaker Information. Sensors, 21(11), Article 11. https://doi.org/10.3390/s21113765</td>
        <td>General smartphone</td>
        <td>Client App</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td>Discussed but not implemented</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Labayen, M., Vea, R., Flórez, J., Aginako, N., &amp; Sierra, B. (2021). Online Student Authentication and Proctoring System Based on Multimodal Biometrics Technology. IEEE Access, 9, 72398–72411. IEEE Access. https://doi.org/10.1109/ACCESS.2021.3079375</td>
        <td>E-Learning plattforms</td>
        <td>Cloud resource</td>
        <td>Impersonation attack</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection / Classification</td>
        <td>Anonymize biometric data*</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Cola, G., Vecchio, A., &amp; Avvenuti, M. (2021). Continuous authentication through gait analysis on a wrist-worn device. Pervasive and Mobile Computing, 78, 101483. https://doi.org/10.1016/j.pmcj.2021.101483</td>
        <td>Smartwatch</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Client</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td>Local processing</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Sanchez, P. M. S., Maimo, L. F., Celdran, A. H., &amp; Perez, G. M. (2021). AuthCODE: A privacy-preserving and multi-device continuous authentication architecture based on machine and deep learning. COMPUTERS &amp; SECURITY, 103, 102168. https://doi.org/10.1016/j.cose.2020.102168</td>
        <td>Computer in in enterprise environment</td>
        <td>Client device</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Aggregation of features over time*</td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Acar, A., Aksu, H., Uluagac, A. S., &amp; Akkaya, K. (2021). A Usable and Robust Continuous Authentication Framework Using Wearables. IEEE Transactions on Mobile Computing, 20(6), 2140–2153. https://doi.org/10.1109/TMC.2020.2974941</td>
        <td>Computer in in enterprise environment</td>
        <td>Client device</td>
        <td>Compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection &amp; Classification</td>
        <td>Transmit features, not raw data*</td>
        <td>Locke the device, alert management and security teams, notify user via e-mail</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Acar, A., Aksu, H., Uluagac, A. S., &amp; Akkaya, K. (2021). A Usable and Robust Continuous Authentication Framework Using Wearables. IEEE Transactions on Mobile Computing, 20(6), 2140–2153. https://doi.org/10.1109/TMC.2020.2974941</td>
        <td>General computer</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td>Noise tolerant template security</td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Acar, A., Ali, S., Karabina, K., Kaygusuz, C., Aksu, H., Akkaya, K., &amp; Uluagac, S. (2021). A Lightweight Privacy-Aware Continuous Authentication Protocol-PACA. ACM Transactions on Privacy and Security, 24(4), 24:1-24:28. https://doi.org/10.1145/3464690</td>
        <td>Virtual Desktops</td>
        <td>Cloud resource</td>
        <td>Compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td></td>
        <td>Lock the deivce, log an alarm, notify the user via e-mail or text message</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Rocha, R., Carneiro, D., &amp; Novais, P. (2021). Continuous authentication with a focus on explainability. In NEUROCOMPUTING (Vol. 423, pp. 697–702). ELSEVIER. https://doi.org/10.1016/j.neucom.2020.02.122</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classificaion</td>
        <td></td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Buriro, A., Gupta, S., Yautsiukhin, A., &amp; Crispo, B. (2021). Risk-Driven Behavioral Biometric-based One-Shot-cum-Continuous User Authentication Scheme. In JOURNAL OF SIGNAL PROCESSING SYSTEMS FOR SIGNAL IMAGE AND VIDEO TECHNOLOGY (Vol. 93, Issue 9, pp. 989–1006). SPRINGER. https://doi.org/10.1007/s11265-021-01654-2</td>
        <td>General smartphone apps</td>
        <td>Client App</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Discussed but not implemented</td>
        <td>Block activities</td>
        <td>Propt for re-authentication</td>
    </tr>
    <tr>
        <td>Barlas, Y., Basar, O. E., Akan, Y., Isbilen, M., Alptekin, G. I., &amp; Incel, O. D. (2020). DAKOTA: Continuous Authentication with Behavioral Biometrics in a Mobile Banking Application. 2020 5th International Conference on Computer Science and Engineering (UBMK), 1–6. https://doi.org/10.1109/UBMK50275.2020.9219365</td>
        <td>Online Banking</td>
        <td>Client App</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Kašys, K., Dundulis, A., Vasiljevas, M., Maskeliūnas, R., &amp; Damaševičius, R. (2020). BodyLock: Human Identity Recogniser App from Walking Activity Data. In O. Gervasi, B. Murgante, S. Misra, C. Garau, I. Blečić, D. Taniar, B. O. Apduhan, A. M. A. C. Rocha, E. Tarantino, C. M. Torre, &amp; Y. Karaca (Eds.), Computational Science and Its Applications – ICCSA 2020 (pp. 307–319). Springer International Publishing. https://doi.org/10.1007/978-3-030-58802-1_23</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td></td>
        <td>Block access to data, inform the owner about the location of the device</td>
        <td></td>
    </tr>
    <tr>
        <td>Xu, W., Shen, Y., Luo, C., Li, J., Li, W., &amp; Zomaya, A. Y. (2020). Gait-Watch: A Gait-based context-aware authentication system for smart watch via sparse coding. Ad Hoc Networks, 107, 102218. https://doi.org/10.1016/j.adhoc.2020.102218</td>
        <td>Smartwatch</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Client</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Shrestha, P., &amp; Saxena, N. (2020). Hacksaw: Biometric-free non-stop web authentication in an emerging world of wearables. Proceedings of the 13th ACM Conference on Security and Privacy in Wireless and Mobile Networks, 13–24. https://doi.org/10.1145/3395351.3399366</td>
        <td>General cloud service</td>
        <td>Cloud resource</td>
        <td>Compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Not use privacy sensitive biometrics*</td>
        <td>Restrict access, alert the user, de-authenticate the session</td>
        <td></td>
    </tr>
    <tr>
        <td>Liang, X., Zou, F., Li, L., &amp; Yi, P. (2020). Mobile terminal identity authentication system based on behavioral characteristics. International Journal of Distributed Sensor Networks, 16(1), 1550147719899371. https://doi.org/10.1177/1550147719899371</td>
        <td>General smartphone apps</td>
        <td>Client App</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Not use privacy sensitive biometrics*</td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Zhu, T., Qu, Z., Xu, H., Zhang, J., Shao, Z., Chen, Y., Prabhakar, S., &amp; Yang, J. (2020). RiskCog: Unobtrusive Real-Time User Authentication on Mobile Devices in the Wild. IEEE Transactions on Mobile Computing, 19(2), 466–483. IEEE Transactions on Mobile Computing. https://doi.org/10.1109/TMC.2019.2892440</td>
        <td>General mobile devices</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Server/Client</td>
        <td>Classification</td>
        <td>Discussed but not implemented</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Sánchez Sánchez, P. M., Huertas Celdrán, A., Fernández Maimó, L., Martínez Pérez, G., &amp; Wang, G. (2019). Securing Smart Offices Through an Intelligent and Multi-device Continuous Authentication System. In G. Wang, A. El Saddik, X. Lai, G. Martinez Perez, &amp; K.-K. R. Choo (Eds.), Smart City and Informatization (pp. 73–85). Springer. https://doi.org/10.1007/978-981-15-1301-5_7</td>
        <td>Computer in in enterprise environment</td>
        <td>Client device</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td>Aggregation of features over time*</td>
        <td>Lock the device</td>
        <td></td>
    </tr>
    <tr>
        <td>Mainali, P., Shepherd, C., &amp; Petitcolas, F. A. P. (2019). Privacy-Enhancing Context Authentication from Location-Sensitive Data. Proceedings of the 14th International Conference on Availability, Reliability and Security, 1–10. https://doi.org/10.1145/3339252.3340334</td>
        <td>General cloud service</td>
        <td>Cloud resource</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td>Hashing biometric data</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Li, Q., &amp; Chen, H. (2019). CDAS: A Continuous Dynamic Authentication System. Proceedings of the 2019 8th International Conference on Software and Computer Applications, 447–452. https://doi.org/10.1145/3316615.3316691</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Client</td>
        <td>Classification</td>
        <td></td>
        <td>Issue a warning</td>
        <td></td>
    </tr>
    <tr>
        <td>Mostafa, H., El-Ramly, M., Elkorany, A. M., &amp; Shaban, H. (2019). Behavio2Auth: Sensor-based Behavior Biometric Authentication for Smartphones. Proceedings of the ArabWIC 6th Annual International Conference Research Track, 1–6. https://doi.org/10.1145/3333165.3333176</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Client</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td>Local processing</td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Hintze, D., Füller, M., Scholz, S., Findling, R. D., Muaaz, M., Kapfer, P., Koch, E., &amp; Mayrhofer, R. (2019). CORMORANT: Ubiquitous Risk-Aware Multi-Modal Biometric Authentication across Mobile Devices. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 3(3), 85:1-85:23. https://doi.org/10.1145/3351243</td>
        <td>General mobile devices</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Unkown</td>
        <td>Unkown</td>
        <td>Unknown</td>
        <td></td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Wu, C., He, K., Chen, J., &amp; Du, R. (2019). ICAuth: Implicit and Continuous Authentication When the Screen Is Awake. ICC 2019 - 2019 IEEE International Conference on Communications (ICC), 1–6. https://doi.org/10.1109/ICC.2019.8761435</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Client</td>
        <td>Classification</td>
        <td></td>
        <td></td>
        <td>-</td>
    </tr>
    <tr>
        <td>Pang, X., Yang, L., Liu, M., &amp; Ma, J. (2019). MineAuth: Mining Behavioural Habits for Continuous Authentication on a Smartphone. In J. Jang-Jaccard &amp; F. Guo (Eds.), Information Security and Privacy (pp. 533–551). Springer International Publishing. https://doi.org/10.1007/978-3-030-21548-4_29</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Client</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td>Local processing</td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Jorquera Valero, J. M., Sanchez Sanchez, P. M., Fernandez Maimo, L., Huertas Celdran, A., Arjona Fernandez, M., De Los Santos Vilchez, S., &amp; Martinez Perez, G. (2018). Improving the Security and QoE in Mobile Devices through an Intelligent and Adaptive Continuous Authentication System. SENSORS, 18(11), 3769. https://doi.org/10.3390/s18113769</td>
        <td>Mobile banking app</td>
        <td>Client device</td>
        <td>Unspecified</td>
        <td>Client</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td>Local processing </td>
        <td>Block the app, block sensitive data and transactions, allow limited payments only</td>
        <td></td>
    </tr>
    <tr>
        <td>Fenu, G., &amp; Marras, M. (2018). Controlling User Access to Cloud-Connected Mobile Applications by Means of Biometrics. IEEE Cloud Computing, 5(4), 47–57. https://doi.org/10.1109/MCC.2018.043221014</td>
        <td>General cloud service</td>
        <td>Cloud resource</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td></td>
        <td>Sign-off the session</td>
        <td></td>
    </tr>
    <tr>
        <td>Fenu, G., Marras, M., &amp; Boratto, L. (2018). A multi-biometric system for continuous student authentication in e-learning platforms. Pattern Recognition Letters, 113, 83–92. https://doi.org/10.1016/j.patrec.2017.03.027</td>
        <td>E-Learning plattforms</td>
        <td>Cloud resource</td>
        <td>Impersonation attack</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Shila, D. M., &amp; Srivastava, K. (2018). CASTRA: Seamless and Unobtrusive Authentication of Users to Diverse Mobile Services. IEEE Internet of Things Journal, 5(5), 4042–4057. https://doi.org/10.1109/JIOT.2018.2851501</td>
        <td>General smartphone apps</td>
        <td>Client App</td>
        <td>Access to client </td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td>Using a random identifier*</td>
        <td>Lock access to sensitive services</td>
        <td>Active authentication foctur such as fingerprint, voice or faice</td>
    </tr>
    <tr>
        <td>Shepherd, C., Akram, R. N., &amp; Markantonakis, K. (2017). Towards trusted execution of multi-modal continuous authentication schemes. Proceedings of the Symposium on Applied Computing, 1444–1451. https://doi.org/10.1145/3019612.3019652</td>
        <td>General computer</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials (sholder surfing)</td>
        <td>Client</td>
        <td>Client</td>
        <td>Classification</td>
        <td>Local processing</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Centeno, M. P., Moorsel, A. V., &amp; Castruccio, S. (2017). Smartphone Continuous Authentication Using Deep Learning Autoencoders. 2017 15th Annual Conference on Privacy, Security and Trust (PST), 147–1478. https://doi.org/10.1109/PST.2017.00026</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Unspecified</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Lee, W.-H., &amp; Lee, R. B. (2017). Implicit Smartphone User Authentication with Sensors and Contextual Machine Learning (arXiv:1708.09754). arXiv. http://arxiv.org/abs/1708.09754</td>
        <td>General smartphone</td>
        <td>Client App</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Client</td>
        <td>Classification</td>
        <td>Anonymize biometric data*</td>
        <td>Lock the device</td>
        <td>Explicit authentication, possibly with biometrics</td>
    </tr>
    <tr>
        <td>Schiavone, E., Ceccarelli, A., &amp; Bondavalli, A. (2017). Continuous Biometric Verification for Non-Repudiation of Remote Services. Proceedings of the 12th International Conference on Availability, Reliability and Security, 1–10. https://doi.org/10.1145/3098954.3098969</td>
        <td>General cloud service</td>
        <td>Cloud resource</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Unknown</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Traoré, I., Nakkabi, Y., Saad, S., Sayed, B., Ardigo, J. D., &amp; de Faria Quinan, P. M. (2017). Ensuring Online Exam Integrity Through Continuous Biometric Authentication. In I. Traoré, A. Awad, &amp; I. Woungang (Eds.), Information Security Practices: Emerging Threats and Perspectives (pp. 73–81). Springer International Publishing. https://doi.org/10.1007/978-3-319-48947-6_6</td>
        <td>E-Learning plattforms</td>
        <td>Cloud resource</td>
        <td>Impersonation attack</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Lee, W.-H., & Lee, R. B. (2017). Implicit Smartphone User Authentication with Sensors and Contextual Machine Learning. 297–308. https://doi.org/10.1109/DSN.2017.24
</td>
        <td>General smartphone apps</td>
        <td>Client App</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Client</td>
        <td>Classification</td>
        <td>Anonymize biometric data*</td>
        <td>Lock the device, refuse access to security-critical data</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Li, Q., Wang, L., Kim, T., &amp; Im, E. G. (2016). Mobile-based continuous user authentication system for cloud security. 2016 IEEE International Conference on Network Infrastructure and Digital Content (IC-NIDC), 176–179. https://doi.org/10.1109/ICNIDC.2016.7974559</td>
        <td>General cloud service</td>
        <td>Cloud resource</td>
        <td>Compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td></td>
        <td>Deny access to remote ressources</td>
        <td></td>
    </tr>
    <tr>
        <td>Shahandashti, S. F., Safavi-Naini, R., &amp; Safa, N. A. (2015). Reconciling user privacy and implicit authentication for mobile devices. Computers &amp; Security, 53, 215–233. https://doi.org/10.1016/j.cose.2015.05.009</td>
        <td>General cloud service</td>
        <td>Cloud resource</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td>Homomorphic encryption</td>
        <td>Log out the user</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Crouse, D., Han, H., Chandra, D., Barbello, B., &amp; Jain, A. K. (2015). Continuous authentication of mobile user: Fusion of face image and inertial Measurement Unit data. 2015 International Conference on Biometrics (ICB), 135–142. https://doi.org/10.1109/ICB.2015.7139043</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Server</td>
        <td>Server</td>
        <td>Classification</td>
        <td></td>
        <td>Log out the user</td>
        <td></td>
    </tr>
    <tr>
        <td>Feng, T., Yang, J., Yan, Z., Tapia, E. M., &amp; Shi, W. (2014). TIPS: Context-aware implicit user identification using touch screen in uncontrolled environments. Proceedings of the 15th Workshop on Mobile Computing Systems and Applications, 1–6. https://doi.org/10.1145/2565585.2565592</td>
        <td>General smartphone apps</td>
        <td>Client App</td>
        <td>Unspecified</td>
        <td>Client</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td>Local processing</td>
        <td>Block access to application</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Khan, H., Atwater, A., &amp; Hengartner, U. (2014). Itus: An implicit authentication framework for android. Proceedings of the 20th Annual International Conference on Mobile Computing and Networking, 507–518. https://doi.org/10.1145/2639108.2639141</td>
        <td>General smartphone apps</td>
        <td>Client App</td>
        <td>Access to client</td>
        <td>Client</td>
        <td>Client</td>
        <td>Unknown</td>
        <td></td>
        <td>Lock the application</td>
        <td>Explicit Authentication with seperate credentials</td>
    </tr>
    <tr>
        <td>Li, L., Zhao, X., &amp; Xue, G. (2013). Unobservable Re-authentication for Smartphones. Network and Distributed System Security Symposium. https://www.semanticscholar.org/paper/Unobservable-Re-authentication-for-Smartphones-Li-Zhao/e86dd9e5ed2033cf7eab97245912b6d21c4c78a3</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Client / Server</td>
        <td>Client</td>
        <td>Classification</td>
        <td>Anonymize biometric data*</td>
        <td>Lock the device, send message with location of the device to the user&#39;s e-mail</td>
        <td>Administrator password</td>
    </tr>
    <tr>
        <td>Crawford, H., Renaud, K., &amp; Storer, T. (2013). A framework for continuous, transparent mobile device authentication. In COMPUTERS &amp; SECURITY (Vol. 39, Issue B, pp. 127–136). ELSEVIER ADVANCED TECHNOLOGY. https://doi.org/10.1016/j.cose.2013.05.005</td>
        <td>General smartphone apps</td>
        <td>Client App</td>
        <td>Access to client and compromised credentials</td>
        <td>Client</td>
        <td>Client</td>
        <td>Classification</td>
        <td>Local processing</td>
        <td>Deny a desired task</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Feng, T., Zhao, X., Carbunar, B., &amp; Shi, W. (2013). Continuous Mobile Authentication Using Virtual Key Typing Biometrics. 2013 12th IEEE International Conference on Trust, Security and Privacy in Computing and Communications, 1547–1552. https://doi.org/10.1109/TrustCom.2013.272</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Client</td>
        <td>Client</td>
        <td>Unknown</td>
        <td>Local processing </td>
        <td>Lock out the user</td>
        <td></td>
    </tr>
    <tr>
        <td>Shi, W., Yang, J., Jiang, Y., Yang, F., &amp; Xiong, Y. (2011). SenGuard: Passive user identification on smartphones using multiple sensors. 2011 IEEE 7th International Conference on Wireless and Mobile Computing, Networking and Communications (WiMob), 141–148. https://doi.org/10.1109/WiMOB.2011.6085412</td>
        <td>General smartphone</td>
        <td>Client device</td>
        <td>Access to client</td>
        <td>Client</td>
        <td>Client</td>
        <td>Classification</td>
        <td></td>
        <td>Lock the device</td>
        <td>Explicit Authentication</td>
    </tr>
    <tr>
        <td>Chow, R., Jakobsson, M., Masuoka, R., Molina, J., Niu, Y., Shi, E., &amp; Song, Z. (2010). Authentication in the clouds: A framework and its application to mobile users. Proceedings of the 2010 ACM Workshop on Cloud Computing Security Workshop, 1–6. https://doi.org/10.1145/1866835.1866837</td>
        <td>General smartphone apps</td>
        <td>Cloud resource</td>
        <td>Access to client and compromised credentials</td>
        <td>Server</td>
        <td>Server</td>
        <td>Anomaly detection</td>
        <td>Hashing of features</td>
        <td>Reject a user request</td>
        <td></td>
    </tr>
    <tr>
        <td>Niinuma, K., Park, U., &amp; Jain, A. K. (2010). Soft Biometric Traits for Continuous User Authentication. In IEEE TRANSACTIONS ON INFORMATION FORENSICS AND SECURITY (Vol. 5, Issue 4, pp. 771–780). IEEE-INST ELECTRICAL ELECTRONICS ENGINEERS INC. https://doi.org/10.1109/TIFS.2010.2075927</td>
        <td>General computer</td>
        <td>Client device</td>
        <td>Access to client and compromised credentials</td>
        <td>Client</td>
        <td>Client</td>
        <td>Anomaly detection</td>
        <td>Local processing</td>
        <td>Lockt the device</td>
        <td>Time decay, hard and soft biometrics</td>
    </tr>
</table>
