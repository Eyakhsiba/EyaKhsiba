

```python
class AboutMe:
    def __init__(self):
        self.name = "Eya Khsiba"
        self.role = "Computer Systems Engineering Student"
        self.specialization = "Embedded Systems & IoT"
        self.location = "Tunisia"
        self.interests = [
            "Embedded Systems",
            "Internet of Things",
            "Computer Vision",
            "Deep Learning"
        ]

    def tech_stack(self):
        return {
            "Programming Languages": [
                "C", "C++", "Python", "Java"
            ],
            "Embedded & Hardware": [
                "Arduino", "ESP32 / ESP32-CAM",
                "Raspberry Pi", "FPGA (NIOS II)"
            ],
            "Computer Vision & AI": [
                "OpenCV", "YOLO", "SVM", "TensorFlow"
            ],
            "IoT & Networking": [
                "MQTT", "HTTP", "WiFi",
                "Cisco Packet Tracer"
            ],
            "Tools & Platforms": [
                "Git", "VS Code",
                "LabVIEW", "Ubuntu", "Google Colab"
            ],
            "Databases & Web": [
                "MySQL", "Flask", "HTML", "CSS", "JS"
            ]
        }
