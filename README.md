#Install torch torchvision
pip install torch torchvision
#Download and Load Dataset
import torchvision.datasets as datasets

# Download CIFAR-10 dataset
train_dataset = datasets.CIFAR10(root='data/', train=True, transform=None, target_transform=None, download=True)
test_dataset = datasets.CIFAR10(root='data/', train=False, transform=None, target_transform=None, download=True)
