import pybullet as p
import pybullet_data


physicsClient = p.connect(p.GUI)  # 物理エンジンに接続

p.setAdditionalSearchPath(pybullet_data.getDataPath())  # pybullet_dataフォルダのパスを通す

planeID = p.loadURDF("plane.urdf")  # 床を読み込む

p.setGravity(0, 0, -9.8)  # 重力を設定する

while True:
    p.stepSimulation()  # ステップシミュレーションを実行
