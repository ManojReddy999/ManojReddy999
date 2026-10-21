# Manoj Reddy Manchala

Robotics and applied-ML engineer. M.S. Mechanical Engineering (Robotics), UC San Diego · B.Tech. Mechanical Engineering, IIT Bombay.

I work on two things: learning-based autonomy in simulation, and applied-AI systems that put models in front of real users. Graduate research at UC San Diego's [Existential Robotics Laboratory](https://existentialrobotics.org/) under Prof. Nikolay Atanasov, on reinforcement learning for autonomous navigation.

Based in India. Open to robotics, perception and applied-AI roles, remote preferred.

### Production systems

- **Growero HRMS** — HR platform in daily use by a company's employees. Next.js 16 / React 19 / TypeScript / Prisma / PostgreSQL, deployed as a PWA. Includes a full Indian payroll engine (PF, PT, ESI, TDS, attendance-driven proration, locked payroll runs), geofenced GPS attendance, leave and expense approval chains, and generated payslip and offer-letter PDFs. Built and maintained solo. *Private repository — happy to walk through it.*
- **FarmInsta Chatbot** — deployed conversational analytics for an agri field-operations team, as AI Tech Lead. Natural-language questions about farmer visits, product demonstrations and team activity are translated to SQL against a read-only copy of the operational database, with conversational context and automatic query repair. *Client project — private.*

### Robotics and autonomy

- **[Reinforcement Learning for Autonomous Navigation](https://github.com/ManojReddy999/Reinforcement-Learning-for-Autonomous-Navigation)** — the UCSD research codebase. Custom MuJoCo / dm_control environments for an Ackermann-steered car, PPO and SAC, and a comparison of CNN, point-cloud GNN and Transformer feature extractors over depth and vehicle state.
- **LocoTransformer v3** — a reproducible successor framework: Ackermann, differential-drive and skid-steer bodies across four world types, a MetaDrive adapter, four visual encoder families, CI, 40 test modules, Docker, and a versioned evaluation protocol with artifact hash contracts.
- **[Visual-Inertial SLAM](https://github.com/ManojReddy999/Visual-Inertial-SLAM)** — IMU and stereo fusion via EKF for pose estimation and landmark mapping.
- **[LiDAR SLAM](https://github.com/ManojReddy999/LiDAR-SLAM)** — scan matching, occupancy grids, texture mapping and pose-graph optimisation.
- **[Motion Planning](https://github.com/ManojReddy999/Motion-Planning)** — search-based and sampling-based planners (A\*, RRT, bidirectional RRT) in 3-D environments.
- **[Mobile Manipulator Control](https://github.com/ManojReddy999/Motion-Control-of-Mobile-Manipulator-Robot)** — full pick-and-place control stack for a KUKA YouBot: kinematics, trajectory generation and feedback control, simulated in CoppeliaSim.

### Vision and control

- **[Comma.ai Calibration Challenge](https://github.com/ManojReddy999/Calibration_Challenge)** — estimating camera pitch and yaw from monocular driving video using optical flow, vanishing-point geometry and a Conv-LSTM.
- **[Model Predictive Control](https://github.com/ManojReddy999/Model-Predictive-Control)** — MPC for navigation over uneven agricultural terrain with elevation and friction effects.

### Other

- **[windows-ipad-control](https://github.com/ManojReddy999/windows-ipad-control)** — use a Windows laptop's keyboard, trackpad and gestures to control an iPad over Bluetooth LE. Universal-Control style, no extra hardware. MIT.

### Tools

Python · PyTorch · NumPy · MuJoCo · dm_control · Stable-Baselines3 · OpenCV · SQL · TypeScript · Next.js · React · Prisma · PostgreSQL · Docker · MATLAB

[Portfolio](https://manojreddy999.github.io/Portfolio/) · [LinkedIn](https://www.linkedin.com/in/manojreddymanchala/)
